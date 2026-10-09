Dashboard for Applications Support
for any issues, reach out to S0D7@pge.com
version 1.0                date 10-09-2026
_________________________________________
This is a Beta Release version:

Features:
1. Track the relevant Incidents and Workorders
2. Track IU-Ready emails and Load-forecast emails
3. Track Dynatrace-initiated problems
4. Track relevant CRQs
Features to be added in next release:
1. Auto-deletion of items from the WO/INC/CRQ list
2. Adoption of proper dataset to define the AI-filters
3. Add Status update to the CRQ section in the primary Dashboard.
4. Figure out and print the sorted CRQ items to be shown on the primary dashboard.
5. Put the Status update to the CRQ landing page
6. Make a settable email-counter to set how many emails to go through
7. Individually link each and every associated files for specified download
Potential:
1. Automated reply to emails
2. Automated email followups
3. Automatic email-forwarding
4. Automatically perform actions to resolve issues
5. Perform and supervise regular monitoring activities like Smoke Tests
6. Efficient and automaticinventory-creation and data-repository maintenance

__________________________________________
Set-up Instructions:
1. Download the files :
a> Dashboard for Applications Support.exe   --- primary function -- run this regularly
ML datasets-------------------------------      .
b> check_if_approved_labels.txt                 |
c> check_if_approved_texts.txt                  |
d> check_if_crq_check_if_approved.txt           | All files from b> are loaded up in a .zip file
e> check_if_crq_check_if_cancelled.txt          | associated files.zip
f> check_if_crq_check_if_draft.txt              | extract these to set them up
g> check_if_crq_check_if_in_progress.txt
h> check_if_crq_check_if_partially_completed.txt
i> check_if_crq_check_if_rejected.txt
j> check_if_crq_check_if_scheduled.txt
k> check_if_crq_check_if_successfully_completed.txt
l> check_if_crq_check_if_unsuccessful.txt
m> check_if_crq_check_if_want_approval.txt
n> check_if_crq_labels.txt
o> cc_engineer_list.txt
p> check_if_want_approval_labels.txt
q> check_if_want_approval_texts.txt
trackers---------------------------------
r> crq_tracker.xlsx
s> ticket_tracker.xlsx
logs-------------------------------------
t> IU_logs.txt
u> ticket_tracker_log.txt
trackers/ app utility--------------------       . find these too in the .zip file
i>      crq_email_links.json
ii>     crq_email_tracker.json
iii>    crq_list.json
iv>     dynatrace_alert_tracker.copy.json
v>      dynatrace_alert_tracker.json
vi>     IU_last_update.json
vii>    load_forecast.json
viii>   ticket_tracker.json
_________________________________________
Folder Structure :
1. All files should be in same Folder - same directory
2. create a folder called 'crq_list_all' inside the mother folder

Look for dashboard.html - open that, it is the mother dashboard. All other dashboards can be navigated to from here