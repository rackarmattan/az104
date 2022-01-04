# Identity and Access

1. Free tier. MFA, user reports, user mgmt.
2. Office365 Apps. Company branding, SLA, Two-Sync between on prem and cloud
3. Premium 1. Hybrid Architeture, Cond. access
4. Premium 2. Identity Protection, ID governance

**Domain**. Area of a network
**Domain controller**. Server that authenticates and authorizes users, logical grouping of AD objects on a network
**Domain Computer**. Registered with a central authN database
**AD object**. A basicc element of AD such as printers, groups, users
**Group Policy Objects**. Virtual collection of policy settings. Controls what AD objects have access to
**Organization Units**. A subdivision within an AD into which you can place AD objects and OUs
**Directory Service**. A service that runs on a domain controller. 

## AAD DS

Managed domain services. 
* Domain joins
* Group policies
* LDAP
* Kerberos / NTLM auth

## AAD Connect

Connect ib orem AD to Azure. Seamless SSO from on prem to Azure. 
* Password hash sync
* Pass-through auth
* Federation integration
* Synchronization
* Health monitoring

## AD Users

Identity for a person or employee. 
* Can track users and their logins
* Track devices
* MFA
* Assign MS licenses
* Admin roles

## AD Groups

Assign permissions to groups rather than users for maintenance. 
* Owners
* Members
* Assign apps to group
* Request to join

## Assign Access Rights

* Direct assignment
* Group assignment
* Rule-based assignment
* External authority assignment

## External identities

Allows people outside the organization to access your apps and resources
* Bring your own IDs
* Google
* Facebook


## Device Identity Management

Mgmt. of physical devices such as phones, tablets, laptops, that are granted access to company resources such as printers, cloud resources via device-based access control.
* Azure AD registered, personal device and logged in with org or personal account
* AAD joined, owned by org and signed in with org account, *only in cloud*
* Hybrid AAD joined, devices owned by an org, AAD DS required, cloud and on prem

### AD Registered Devices

Registered to AAD without getting organizational account to sign in to the device. Bring your own device or mobile devices. 
* Mobile Device Management (MDM), control the entire device, can wipe data from it
* Mobile Application Management (MAM), publish, push, configure, secure, monitor, and update mobile apps for your users. 

MDM and MAM managed from **Intune, AAD Premium 2**. Part of Microsoft Endpoint Manager and MS Enterprise Mobility + Security (EMS). Intune = Endpoint Manager = EMS

### EMS

Remote working safe. Umbrella for several services:
* AAD
* Microsoft Intune




