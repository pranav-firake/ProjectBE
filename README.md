# ProjectBE

./admin:
list_administrators.html.erb        show_admin.html.erb
list_instructors.html.erb           _show.html.erb
list_super_administrators.html.erb  show_instructor.html.erb
new_administrator.html.erb          show_super_admin.html.erb
new_instructor.html.erb

./advertise_for_partner:
edit.html.erb  new.html.erb  _qualifications.html.erb  show.html.erb

./advice:
edit_advice.html.erb  list.html.erb

./assessment360:
all_students_all_reviews.html.erb

./assignments:
associate_assignment_with_course.html.erb  list_submissions.html.erb
delayed_mailer.html.erb                    new.html.erb
delete.html.erb                            _reserve_topic.html.erb
edit                                       show.html.erb
edit.html.erb                              thought.html.erb
index.html.erb

./assignments/edit:
_calibration.html.erb  _general.html.erb      _review_strategy.html.erb
_due_dates.html.erb    _late_policy.html.erb  _rubrics.html.erb

./assignment_survey_questionnaires:
assign.html.erb  list.html.erb

./auth:
_login.html.erb  login.html.erb  logout.html.erb

./automated_metareviews:
list.html.erb

./bookmarks:
bookmark_rating.html.erb  edit.html.erb  list.html.erb  new.html.erb

./content_pages:
edit.html.erb   _home.erb      new.html.erb   view_default.html.erb
_form.html.erb  list.html.erb  show.html.erb  view.html.erb

./controller_actions:
edit.html.erb   index.html.erb  new.html.erb
_form.html.erb  list.html.erb   show.html.erb

./course:
_add_individual.html.erb  edit.html.erb     _ta.html.erb
add_ta.js.erb             new.html.erb      view_teaching_assistants.html.erb
_course.html.erb          remove_ta.js.erb

./course_participants:
list.html.erb

./eula:
display.html.erb

./export_file:
_assignment_teams.html.erb     _export_details.html.erb  _users.html.erb
_course_participants.html.erb  _scores.html.erb
_course_teams.html.erb         start.html.erb

./grades:
_author_feedbacks.html.erb         _submitted_files.html.erb
_author_feedback_tab.html.erb      _submitted_work.html.erb
_author.html.erb                   _summary_reviews.html.erb
edit.html.erb                      _tabbed_participant.html.erb
_heat_grid_tab.html.erb            _tabbed_reviews.html.erb
_meta.html.erb                     _tabbing.html.erb
_metareviews.html.erb              _team_charts.html.erb
_metareviews_tab.html.erb          _team.html.erb
_participant_charts.html.erb       _teammate.html.erb
_participant.html.erb              _teammate_reviews.html.erb
_participants_statistics.html.erb  _teammate_reviews_tab.html.erb
_participant_title.html.erb        _team_review_statistics.html.erb
_questionnaire.html.erb            _teams.html.erb
_reviews.html.erb                  _team_statistics.html.erb
_reviews_tab.html.erb              _team_title.html.erb
_review_table.html.erb             view.html.erb
_scores.html.erb                   view_my_scores.html.erb
_statistics_tab.html.erb           view_team.html.erb
_submissions.html.erb

./impersonate:
start.html.erb

./import_file:
start.html.erb

./institution:
edit.html.erb  _form.html.erb  list.html.erb  new.html.erb  show.html.erb

./instructions:
home.html.erb

./join_team_requests:
create.html    _list_received.html.erb  new.html.erb
edit.html.erb  _list_sent.html.erb      show.html.erb

./late_policies:
edit.html.erb  _form.html.erb  index.html.erb  new.html.erb  show.html.erb

./layouts:
application.html.erb  question_types.html.erb  _tabpanel_js.html.erb
_favicon.html.erb     standard.html.erb        _tabpanel_list.html.erb

./mailer:
generic_message.html.erb
generic_message.text.erb
notify_grade_conflict_message.html.erb
partials
request_user_message.html.erb
suggested_topic_approved_message.html.erb
suggested_topic_approved_message.text.erb
sync_message.html.erb
sync_message.text.erb

./mailer/partials:
_limit_notify_html.html.erb
_limit_notify_plain.html.erb
_metareview_deadline_test_html.html.erb
_metareview_deadline_test_plain.html.erb
_new_submission_html.html.erb
_new_submission_plain.html.erb
_register_html.html.erb
_register_plain.html.erb
_review_deadline_test_html.html.erb
_review_deadline_test_plain.html.erb
_send_password_html.html.erb
_send_password_plain.html.erb
_submission_deadline_test_html.html.erb
_submission_deadline_test_plain.html.erb
_update_html.html.erb
_update_plain.html.erb
_user_welcome_html.html.erb
_user_welcome_plain.html.erb

./markup_styles:
edit.html.erb  _form.html.erb  list.html.erb  new.html.erb  show.html.erb

./menu_items:
_breadcrumbs.html.erb  _item_parent_list.html.erb  show.html.erb
edit.html.erb          list.html.erb               _suckerfish.html.erb
_form.html.erb         _menubar.html.erb
_item_list.html.erb    new.html.erb

./notifications:
edit.html.erb  _form.html.erb  index.html.erb  new.html.erb  show.html.erb

./participants:
add.js.erb              list.html.erb          select.html.erb
change_handle.html.erb  _participant.html.erb  view_publishing_rights.html.erb

./password_retrieval:
check_reset_url.html.erb  forgotten.html.erb  reset_password.html.erb

./plagiarism_checker_assignment_submissions:
new.html.haml

./popup:
author_feedback_popup.html.erb               reviewer_details_popup.html.erb
automated_metareview_details_popup.html.erb  team_users_popup.html.haml
participants_popup.html.erb                  view_review_scores_popup.html.erb

./profile:
edit.html.erb  _handle.html.erb  _limit.html.erb

./publishing:
grant.html.erb  view.html.erb

./questionnaires:
copy_questionnaire.html.erb    list_questionnaires.html.erb
_course.html.erb               new.html.erb
delete_questionnaire.html.erb  _new_question_template.html.erb
edit_advice.html.erb           new_quiz.erb
edit.html.erb                  _new_quiz_script.html.erb
edit_questionnaire.html.erb    _questionnaire.html.erb
initial                        _quiz_questionnaire.html.erb
list.html.erb                  view.html.erb

./reputation_web_service:
client.html.erb

./response:
_accordion.html.erb       response.html.erb
_advice.html.erb          show_calibration_results_for_student.html.erb
_fileUpload.html.erb      _submitted_files.html.erb
pending_surveys.html.erb  view.html.erb

./review_mapping:
_aggregate_distribution.html.haml    _review_report.html.erb
_calibration_report.html.erb         _searchbox.html.erb
distribution.html.haml               select_metareviewer.html.haml
_feedback_report.html.erb            select_reviewer.html.haml
list.html.haml                       _submitted_files.html.haml
list_mappings.html.haml              _summary_report.html.haml
_list_review_mappings.html.erb       _summary_reviewee_report.html.haml
list_sortable.html.erb               _teammate_review_report.html.erb
_plagiarism_checker_report.html.erb  _team_score.html.erb
response_report.html.haml            unsubmit_review.js.erb
_review_distribution.html.haml

./roles:
edit.html.erb   index.html.erb  new.html.erb
_form.html.erb  list.html.erb   show.html.erb

./shared:
_error_messages.html.erb  _flash_notifications.html.erb  _header.html.erb
_flash_messages.html.erb  _footer_message.html.erb       _navigation.html.erb

./shared_scripts:
_add_individual.html.erb  _letters.html.erb  _selectTable.html.erb
_back.html.erb            _pages.html.erb    _user_list.html.erb

./signup:
signup_topics.html.erb  _waitlisted_choosers.html.erb

./sign_up_sheet:
_actions.html.erb                      new.html.erb
_add_signup_topics.html.erb            _num_of_choosers.html.erb
_add_signup_topics_staggered.html.erb  _num_waiting.html.erb
_add_topics.html.erb                   _reserve_topic.html.erb
_all_actions.html.erb                  show_team.html.erb
_available_slots.html.erb              signup_as_instructor.html.erb
_choose_line_color.html.erb            _suggested_topic.html.erb
_due_dates.html.erb                    _table_header.html.erb
edit.html.erb                          _table_line.html.erb
intelligent_topic_selection.html.erb   _topic.html.erb
list.html.erb                          _topic_names.html.erb
_micropayment.html.erb                 _waitlisted_choosers.html.erb

./site_controllers:
edit.html.erb   index.html.erb  list.html.erb  show.html.erb
_form.html.erb  _list.html.erb  new.html.erb

./student_quizzes:
finished_quiz.html.erb  _responses.html.erb        _set_dynamic_quiz.html.erb
index.html.erb          review_questions.html.erb  take_quiz.html.erb

./student_review:
list.html.erb        _set_dynamic_metareview.html.erb
_responses.html.erb  _set_dynamic_review.html.erb

./student_task:
_eula.html.erb  others_work.html.erb         view.html.erb
list.html.erb   _publishing_rights.html.erb

./student_teams:
edit.html.erb  view.html.erb

./submission_records:
index.html.erb

./submitted_content:
edit.html.erb        _self_review.html.erb      view.html.erb
_hyperlink.html.erb  _submitted_files.html.erb
_main.html.erb       _title.html.erb

./suggestion:
edit.html.erb   list.html.erb  show.html.erb          student_view.html.erb
_form.html.erb  new.html.erb   student_edit.html.erb  _suggestion.html.erb

./survey:
assign.html.erb  list.html.erb

./survey_deployment:
generate_statistics.html.erb  new.html.erb
list.html.erb                 view_responses.html.erb

./survey_response:
begin_survey.html.erb  create.html.erb  view_responses.html.erb
comments.html.erb      submit.html.erb

./system_settings:
edit.html.erb  _form.html.erb  list.html.erb  new.html.erb  show.html.erb

./teams:
edit.html.erb   list_assignments.html.erb  new.html.erb
_form.html.erb  list.html.erb

./teams_users:
_form.html.erb  list.html.erb  _members.html.erb  new.html.erb

./tree_display:
actions           list.html.erb          _row_footer.html.erb
confirm.html.erb  _listing.html.erb      _row_header.html.erb
_entry.html.erb   _page_footer.html.erb
_folder.html.erb  _page_header.html.erb

./tree_display/actions:
_no_actions.html.erb  _teams_actions.html.erb  _teams_users_actions.html.erb

./user_pastebins:
_save_text_macros.html.erb

./users:
edit.html.erb           list_pending_requested.erb  request_new.html.erb
_email.html.erb         _name.html.erb              show.html.erb
_institutions.html.erb  new.html.erb                _user.html.erb
keys.html.erb           _password.html.erb
list.html.erb           _prefs.html.erb

./versions:
index.html.erb  _pagination.html.erb  search.html.erb  show.html.erb
