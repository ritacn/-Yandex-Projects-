# Project name:

## AB test result analysis


| Skills and Tools Used: | Tasks: | Project description: |
| :-------------------- | :--------------------- |:---------------------------|
| Matplotlib, Pandas, Python, Seaborn, Сohort Analysis,Product Metrics | Our task is to evaluate the results of an A/B test. We have a dataset with user actions, a technical specification and several auxiliary datasets. We need to: assess test execution correctness; analyse test results and check test audience overlap with competing test and coincidence of test and marketing events.| Gross errors in the test were detected, their causes and recommendations for avoiding them were given. A discrepancy was found between the test and the provided terms of reference. The z-test was also used to evaluate the results in the test and control groups|

 **Data description**
 
ab_project_marketing_events.csv - marketing events calendar for 2020.

 - name - name of the marketing event;
 - regions - regions where the marketing campaign will be carried out;
 - start_dt - date when the campaign will start;
 - end_dt - date when the campaign ends.
 
 final_ab_new_users.csv - users who registered between December 7 and 21, 2020.

 - user_id - user ID;
 - first_date - date of registration;
 - region - region of the user;
 - device - device from which the registration was made.
 
final_ab_events.csv - actions of new users from December 7, 2020 to January 4, 2021.

 - user_id - user ID;
 - event_dt - purchase date and time;
 - event_name - event type;
 - details - additional data about the event. For example, for purchases, purchase, this field stores the purchase price in dollars.
 
 final_ab_participants.csv - table of test participants.

 - user_id - user ID;
 - ab_test - test name;
 - group - user group.
