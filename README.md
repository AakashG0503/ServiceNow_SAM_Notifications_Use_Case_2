                                                              ServiceNow SAM Notifications: Use Case-2

Story - As a SAM Analyst/ServiceNow Developer, I need to create or trigger the notification to the owners of the license entitlements which are going to expire in next 30, 60, and 90 days.

Solution - There are 5 steps that we need to follow in order to achieve this requirement in ServiceNow.

STEP 1: — Open an Entitlement (alm_license) Table and Set the Filter on “End Date” and “License Type” Field.
STEP 2: — Open a Scheduled Jobs (sysauto) Table and Create New Scheduled Job by clicking on the New Button.
STEP 3: — Open an Event Registry (sysevent_register) Table and Create New Event by clicking on the New Button.
STEP 4: — Open Notifications (sysevent_email_action_list) Table and Create New Notification by clicking on the New Button.
STEP 5: — Open a Notification Email Script (sys_script_email_list) Table and Create New Email Script by clicking on the New Button.

End to End Guidance is also available on my Medium Account - https://medium.com/@aakashgarg0503
