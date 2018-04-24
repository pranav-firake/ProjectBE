bamboos-MacBook-Pro:Python-get-CIDR-of-interfaces-on-MacOS bamboo$ cat cidrIpAddress.py 
import os
import sys
import re
import subprocess

nwDevicesTemp = (subprocess.check_output(['networksetup', '-listallhardwareports']).splitlines())

nwDevices=[]

for devName in nwDevicesTemp:
    if "Device:" in devName:
        nwName = re.sub('Device: ', '', devName)
        nwDevices.append(nwName)

print nwDevices

for devName in nwDevices:
    try:
        ipAddr = subprocess.check_output(['ipconfig', 'getifaddr', devName])
        if len(ipAddr):
            netMask = subprocess.check_output(['ipconfig','getoption', devName, 'subnet_mask'])
            NetMaskBits = sum([bin(int(x)).count("1") for x in netMask.split(".")])
            cleanIp = ipAddr.rstrip()
            print devName +": "+ str(cleanIp) +"/"+ str(NetMaskBits)
    except:
        pass

    
bamboos-MacBook-Pro:Python-get-CIDR-of-interfaces-on-MacOS bamboo$ python cidrIpAddress.py 
['en0']
en0: 10.0.2.15/24
bamboos-MacBook-Pro:Python-get-CIDR-of-interfaces-on-MacOS bamboo$ 
