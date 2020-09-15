Notes to agent:

Overview

This knowledge article should be used when a user receives the error message receives either of the error messages below when they attempt to access a SharePoint Online (SPOL).

ERROR: Access Denied
ERROR: This site has not been shared with you.
Updated: 10/30/2019

 

 Routing Category 	 Software 
 Routing Subcategory	 Desktop Application 
 Affected Service	 N/A
 Assignment Group	 Enterprise SharePoint Team 
 

Agent Action

Probing Questions

Ask the user for the URL of the SharePoint they are accessing:
If the URL contains dvagov.SharePoint the SharePoint is located on SPOL, continue to Step 1.
If the URL does not contain dvagov.SharePoint the SharePoint is still On-Premises, search for alternative On-Premises SharePoint knowledge.
Ask the user if they previously had access to this SharePoint?

If yes, proceed to Step 1.
If No:
Ensure all required fields are documented appropriately in the incident.
Document the following additional information in the incident:
Full URL for the SharePoint site
Attach this knowledge article to the incident.
Escalate the incident using the routing information above. Manually enter Enterprise SharePoint Team into the Assignment Group Field.

1. Guide the user through the End User Solution.

2. Ensure all required fields are documented appropriately in the incident.

3. Document the following additional information in the incident:

Full URL for the SharePoint site
4. Attach this knowledge article to the incident.

5. Determine whether the user's issue is resolved:

If yes, resolve the incident.
If no, escalate the incident using the routing information above. Manually enter Enterprise SharePoint Team into the Assignment Group Field.
 

End User Solution

If you are receiving one of the error messages below when you attempt to access a SharePoint Online (SPOL) site, please be advised of the following information.

ERROR: Access Denied

ERROR: This site has not been shared with you

SharePoint uses access controls to ensure that only authorized employees can use a particular site or information and site access is defined by user roles. Refer to the appropriate guidance below based on whether this is your first time accessing the site:


First Time Access

If this is the first time you have attempted to access this SharePoint site and you receive one of the error messages above you need access to a site, submit a request to the site owner. Often, when you try to access a SPOL site, you will land on a page with a request form that is sent directly to the site owner. If you do not reach this request form, contact your site's appropriate SharePoint farm administrator, who can identify the site owner for you.


Subsequent Login Attempts

If you have recently lost access to a site that you frequently use or a site that is otherwise universally accessible - like the O365 Training Center or SPO Training Resources sites - your browser, desktop, or user profile may be affected by a partial update of group policies. To resolve this error by following the steps below to force the update:

1. Open your Windows Start Menu and search: Command Prompt

2. Click on the Command Prompt or CMD

3. Type the following command and press enter: GPupdate /force

4. Restart your computer. Many policies cannot be updated until Windows restarts.

NOTE: It is unlikely that Office of Information and Technology staff are familiar enough with your position and the site you are trying to access to safely decide whether you should have access. Therefore, OIT does not grant access to any SharePoint Resources except their own and unless the organizational sponsor for that site has a written directive.

It is also recommended that site owners who need help understanding access controls and permissions refer to the O365 Training Center and the SharePoint Training Resources site before escalating a ticket to OIT for support.


If you are still experiencing issues with logging into SharePoint Online, contact the Enterprise Service Desk using one of the methods listed below:

Self-Service: Create Incident 
Phone: 855-673-4357
TTY (Hearing Impaired Only): 512-326-6638
These lines are available 24/7
