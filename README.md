# Azure-AD-Roles

What are Azure AD roles?

- Azure AD role are built-in roles used to manage <strong> Azure AD resources </strong>. 
- There are several Azure AD Roles and they can be used to:
- Create or edit users
- Assign admin roles to others
- Reset user passwords
- Manage user licenses
- Manage domains
- And MORE.

Some Azure AD roles are:
- Global Administrator
- - Manage access to ALL administarive features in Azure AD, as well as services that federate to Azure AD
- - Assign administrator roles to others
- - Reset the password for any users and all other administrators
- <strong> <em> The person who signs up for the Azure AD tenant becomes a Global Administrator </strong> </em>
- User Administrator:
- - Create and manage all aspects of users and groups
- - Manages support tickets
- - Change passwords for users, Helpdesk administrators, and other user Administrators
- Billing Administrator
- - Makes purchases
- - Manages subscriptions
- - Manage support tickets
- - Monitors service health


<strong> <em> To view the list of built-in roles within Azure AD, navigate to Azure AD > Click on the Roles and Administrators blade. </em> </strong> 

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/166802229-da4c29b8-4789-4f59-a041-691b7c9def58.png" height="100%" width="100%" alt="AZ Active Directory Roles"/>
  
<p/>

# Azure Roles (RBAC) vs Azure Active Directory Roles

Azure roles control permissions to manage Azure resources, while Azure AD roles control permissions to manage Azure Active Directory resources.
# RBAC has three basic roles that apply to all resource types:
- Owner
- This role has full access to all the resources and can delegate access to others.
 
- Contributor
- This role can create and manage all types of resources, but can’t grant access to other users and groups.
 
- Reader
- This role can view existing Azure resources.


# Summary
 - Azure AD roles are used to manage access to Azure AD resources, whereas Azure roles are used to manage access to Azure resources.
 - The scope of Azure AD roles is at the tenant level, whereas the scope of Azure roles can be specified at multiple levels including management group, subscription, resource group, resource.
