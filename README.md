# UiPath-Open-E
UiPath Library for Open-E plattform

## Library dependencies
* UiPath.Excel.Activities >= 2.7.2
* UiPath.Mail.Activities >= 1.7.2
* UiPath.System.Activities >= 19.10.1
* UiPath.UIAutomation.Activities >= 19.11.0

## Application dependencies
* Internet Explorer

## Workflows
### Login to Open-E
#### Description
Description: Opens up Open-E and logs in 

Pre: n/a
Post: Logged in to Open-E

#### Arguments
* in_OpeneURL: URL to Open-E (String) [Required]
* in_SiteName: Friendly sitename that will be used in logs (String) [Optional]
* in_Username: Username for Open-E (String) [Required]
* in_Password: Password for Open-E (SecureString) [Required]

### Open IssueList 'Mina'
#### Description
Description: Workflow navigates to issuelist "Mina"

Pre: Successfully logged in to Internservice
Post: Successfully opened issuelist "Mina"