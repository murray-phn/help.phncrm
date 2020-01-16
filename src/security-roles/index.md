## Overview

Security Roles (Permissions) allow administrators to choose which staff members can read, create, update or delete records of different entities.

Create = Can create records of this entity
Read = Can read records of this entity
Write = Can update/edit records of this entity
Delete = Can delete records of this entity
Append = 
Append To = 
Assign = Can make another User the Owner of a record

The example below shows the 'Team Member' security role. This means that any User given the 'Team Member' role can do anything to Account records except delete them permanently (they can still deactivate them). 
<img src="sec-roles-example.png" />

## Assigning Security Roles

If you are a CRM Administrator, you can give Users additional Security Roles to allow them to manage records of different types. The User's position and responsibilities will determine what Roles they require.

The Security Roles are set up to be very simple. Typically there is a Security Role for each entity (e.g. Controlled Documents, CPRA, Risk). Most Security Roles give 'Read, Create, Write, Append, Assign' permission for that entity. Remember, auditing is enabled for most entities so all changes are tracked.

[See the list of Security Roles](/sec-roles)

How to change a User's Security Roles:

1. Go to the list of Users and select the User.

1. In the command bar, click 'Manage Roles'.

1. Check/Uncheck the Security Roles you want the User to have. Click 'Ok' to apply the changes.

<img src="assign_security_role.gif" />

## List of Security Roles

See below the list of Security Roles.

### Administrator
**Notes:** Delete

**User Settings:** Create, Read, Write, Delete, Append To

**Activity Category:** Delete, Assign

### Controlled Documents
**Controlled Documents:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### CPRA
**CPRA:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### Data Dictionary
**Definition:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### Devices
**Device, Device Allocation:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### Dynamics 365 App for Outlook User

This Security Role is provided by Microsoft. It enables a User to use the 'Dynamics 365 App for Outlook'.

### Legislation
**Legislation, Legislative Body:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### Risks
**Risk, Risk Action:** Create, Write, Delete (if record owner), Append, Append To, Assign

### Software
**Software, Software Allocation:** Create, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

### User Management
**User:** Write, Append, Append To

**User Settings:** Read, Write, Append To

Assign manager for a User
Assign Territory to User
Approve Email Addresses for Users or Queues
Assign position for a user
Enable or Disable User
Reparent user

### Team Member
**Account:** Create, Read, Write, Append, Append To, Assign (if record owner)

**Contact**: Create, Read, Write, Append, Append To, Assign

**Note**: Create, Read, Write (if record owner), Delete (if record owner), Append (if record owner), Append To (if record owner), Assign (if record owner)

**Report:** Create, Read, Write (if record owner), Delete (if record owner), Append (if record owner), Append To, (if record owner), Assign (if record owner)

**Marketing List:** Create, Read, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

**Activity Category:** Create, Read, Write, Append, Append To

**Agreement:** Create, Read, Write, Delete (if record owner), Append, Append To, Assign

**Contact Role, Contact Role Type:** Create, Read, Write, Delete (if record owner), Append, Append To, Assign (if record owner)

**Definition:** Read, Append, Append To

**EULA:** Create, Read, Write, Delete (if record owner), Append, Append To

**Risk, Risk Action:** Create, Read, Write (if record owner), Append (if record owner), Append To (if record owner), Assign (if record owner)

Create Quick Campaign
View Audit Partitions, History, Summaries
Bulk Edit