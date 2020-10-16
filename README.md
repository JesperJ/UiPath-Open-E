# Open-E
Open-E Library
Version 1.0.2 built with Studio version 19.10.2.0 with expression language VisualBasic
# Dependencies
* UiPath.Excel.Activities [2.7.2]
* UiPath.Mail.Activities 1.7.2
* UiPath.System.Activities 19.10.1
* UiPath.UIAutomation.Activities 19.11.0
## Worflows
### Login to Open-E.xaml
#### Description
Description: Opens up Open-E and logs in 

Pre: n/a
Post: Logged in to Open-E
#### Arguments
| Argument | Description | Type |
| --- | --- | --- |
| in_OpeneURL | URL to Open-E (Required) [String] | InArgument(x:String) |
| in_SiteName | Friendly sitename that will be used in logs (Optional) [String] | InArgument(x:String) |
| in_Username | Username for Open-E (Required) [String] | InArgument(x:String) |
| in_Password | Password for Open-E (Required) [SecureString] | InArgument(ss:SecureString) |
### NavigateTo_IssueList_OpenE.xaml
#### Description
Description: Workflow navigates to issuelist "Mina"

Pre: Successfully logged in to Internservice
Post: Successfully opened issuelist "Mina"
#### Arguments
| Argument | Description | Type |
| --- | --- | --- |
