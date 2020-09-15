KB0010957  -  v19.0

Notes to agent:

Overview

This knowledge article should be used when a user is having issues with a SharePoint site and there not an issue-specific knowledge article that specifically addresses the user's issues, which includes the following:

Issue/Error Accessing SharePoint Site
Issue/Error Accessing Files on a SharePoint Site
Requesting Access to a SharePoint Site/Folder/File
Content Missing from SharePoint Site
Help with SharePoint Metrics/Analytics
Help with Moving SharePoint Files/Folders/Libraries
SharePoint Permissions
Vanity URLs for SharePoint
NOTE: Know the difference between a shared drive and a SharePoint site: 

A shared drive provides access to a folder on a server somewhere users can store documents.  The path to a shared folder is usually formatted like the following example:
F:\\Administrative\Training2018\Certificates
SharePoint is a web application that allows multiple users access to the same pool of documents/calendars/other items.  Access can be restricted at various levels, and document version history is automatic. The web address for a SharePoint site is usually formatted like the following examples:
https://raportal.vpn.va.gov/Main1/
https://vaww.visn1.portal.va.gov/
The number of SharePoint site collections is into the hundreds of thousands. Each one of those is supported/hosted by any one of hundreds of possible entities.
If the user is having issues with a shared network drive, see KB0010839.

If the user is an OGC User that is having problems with an OGC Sharepoint site, refer to KB0108260.

Updated: 07/09/2019


Routing Category 	See below.
Routing Subcategory 	See below.
Affected Service	See below.
 

 

Agent Action

 
1. Ask whether the user needs assistance with an Enterprise Program Management Office (EPMO) SharePoint Site,

If yes, refer to KB0092060. EPMO sites either:  
Begin with https://vaww.oed.portal.va.gov/
Have addresses that include epmo or oitepmo

If no, go to Step 2.
2. Determine whether there is an issue-specific knowledge article that addresses the user's issue.

If yes, follow the instructions provided in the issue-specific knowledge article.
If no, go to Step 3.
3. Attempt to locate the SharePoint site and POC/Group using the SharePoint Farms and POC page:

Open the SharePoint Farms and POCs page.
Ask the user for the SharePoint website address.
NOTE: You must search by website address because the SharePoint page name is not listed on the SharePoint Farms and POCs page.
Press CTRL+F to open a search box.
Type the website address into the search box.

NOTE: Search using only the root site, rather than the sometimes very long website address. See examples below:
Search vashare.oit.va.gov
instead of vashare.oit.va.gov/sites/default/sharedDocuments...
Search visn5.portal.va.gov
instead of visn5.portal.va.gov/SitePages/OM/lists/...

If the site is found, follow the steps below:
Document the appropriate information in the Work Notes. Include the following:
Complete Site URL
Site POC and Contact information
SNOW Assignment Group (if available)
Attach this knowledge article to the incident.
Determine whether the assignment group is valid in ServiceNow:
If yes, escalate the incident using the routing information below. Manually enter/select the appropriate Assignment Group listed the SharePoint Farms site in the Assignment Group field.

NOTE: For issues with sites including “vashare” in the URL (such as “vaww.vashare.oit.va.gov”), as well as those hosted by “CRRC," manually enter/select IO.SS.FF.SharePoint in the to Assignment Group. This group also owns the SharePoint Farms and POCs site.

Routing Category 	 Software
Routing Subcategory	 Desktop Application
Affected Service	 N/A
Assignment Group	 Group from SP Farms site 
If no:
Provide the contact information for the site POC to the user.
Instruct the user to contact the site POC.
Document the appropriate information in the Work Notes. 
Attach this knowledge article to the incident. 
Resolve the incident.

If the site was found, but with the POC information is not listed or is invalid, proceed to Step 4.
If the site was not found, proceed to Step 4 and follow the instructions for locating a site using the VA Web Registry.
4. Attempt to locate the SharePoint site and POC/Group using the VA Web Registry page, if not found in previous sub-step:

Open the VA Web Registry page.
Search by root website address and click View.
Searching by URL: Type in the entire website address or a portion of the address. For example, typing “comm” in the URL search will result in a listing of all registered websites with comm as part of the website address, such as http://vaww.va.gov/vhacio-comm.
Determine whether the site is listed:

If the site is listed, follow the steps below:
Provide the user with the site POC's contact information.
Document the appropriate information in the Work Notes. Include the following:
Complete Site URL
Site POC and contact information
Attach this knowledge article to the incident.
Resolve the incident.

If the site is not listed, go to Step 5. 
5. Document the appropriate information in the Work Notes. Include the following:

The complete URL of the SharePoint site that the user needs support for
A note indicating both the Farms and POC list and the VA Web Registry were searched with no results
6. Attach this knowledge article to the incident.

7. Escalate the incident using the routing information below:

 Routing Category 	 Affected Service
 Routing Subcategory	 N/A
 Affected Service	 Microsoft SharePoint
