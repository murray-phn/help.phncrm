# Changelog

Changes to the PHN CRM are shown below.

______

0.2.1.09 | 28th Jan 2020

- Added fields to Contact: POA, LGA, STE
- Added Google Map to Contact Form that finds Google place and sets lat/lng fields
- Added Real-Time Process for Contact that sets the values for POA, LGA and STE when SSC changes
- Fixed script error when Contact Role was saved

0.2.1.08

- Team Member' Security Role can now delete Contact Roles not Owned by them.
- Added 'My Open Activities' view
- Removed 'Merge Records' Security Role - Team Member Role already contains this permission
- Added custom help URLs for most entities (https://help.phncrm.com.au/)
- Enabled auditing for the following entities: Activity Category, Agreement, Appointment, Contact, Contact Role, EULA, Note, Phone Call, Task, User
- Removed 'EFT' field from Contact Role views and forms. Can be made visible per PHN
- Added new view to 'User' entity that displays Mailboxes not configured for syncing

0.2.1.07

- 'Team Member' Security Role can now Assign any Account.

0.2.1.06

- Added 'Contact Role Types' Security Role to lock down edits of records
- Removed write/delete permissions for 'Contact Role Types' from 'Team Member' security role
- Added 'Modified On' and 'Modified By' to default view for 'Contact Role Types'
- Added 'Activity Categories' Security Role to lock down edits of records
- Removed write/delete permissions for 'Activity Categories' from 'Team Member' security role

0.2.1.05

- Added 'Marketing List' to site map (temp request by PHN)
- Modified default view for 'Reports' to exclude the system-default reports created by Microsoft
- Added some permissions to the Team Member security role
- Made 'Accounts I own' the default view
- Removed user-level 'delete' permission for Accounts from 'Team Member' role
- 'Team Member' role can now delete Contacts
- Added permission for users to 'pin' views to default (per-user)
- Configured entities in the 'quick create' list

0.2.1.04

- Added some charts and dashboards for Activities entity
- Configured Quick Find view for 'Contact Role Type' entity
- Configured Quick Create Form for 'Contact Role' entity
- Fixed sorting for Activity views
- Changed default charts for Accounts
- Gave the 'Administration' Security Role permission to change user settings
- Updated the 'Task' Form and Views

0.2.1.03

- Configured the 'Activity Report' Report

0.2.1.02

- Changed the way 'Compose Email' button creates emails
- Removed Events from Site Map
- Some renaming of tabs on Forms

0.2.1.01

- Added 'Tasks' entity to D365 App for Outlook. Also added 'Tasks' to the Business Area, and moved the 'Activities' link
- Added 'Date Created' to 'Activity' entity view (All Activities)
- Configured Quick Find views for all geographical entities

0.2.1.00

- Added 'CPRA' module (Counter-Party Risk Assessments)
- The 'Instant Search' page now returns CPRA records
- Added field 'Record URL' to Account, including 'OnCreate' process which sets the URL

0.2.0.23

- Fixed Security Roles for 'Activity Category' entity

0.2.0.21

- Added 'Additional Phone' field to Contact entity
- Added 'Activity Category' entity for tracking activities against (Set Regarding)
- Configured the site map for the 'App for Outlook' model-driven app
- Configured Forms for Phone Call, Appointment and Email entities. Includes custom code
- Removed duplicate field 'Patient Information Systems'
- Removed duplicate field 'IT Provider'

0.2.0.20

- Made required changes to the Contact Views, and Contact Role entity

0.2.0.19

- Fix for 'Inactive Risks' view

0.2.0.18

- Added EwR Dashboard

0.2.0.17

- Built the Fields, Forms, Views and JavaScript for the entities 'Contact Role' and 'Contact Role Type'

0.2.0.12

- First implementation of EWRR (Enterprise-Wide Risk Register)

0.2.0.11

- Renamed 'Policy' entity to 'Controlled Document', including associated Fields, Forms and Views
- Begun change log