# Class 08 Reading Notes

## 5 Steps to RBAC

1) Role Based Access control is a system that gives users privileges based on the access they were assigned

2) A role/permission hierarchy that i would implement would be a tier system where given the profile the user would have higher permissions then others, for example 'reddit' users this similar hierarchy, there are users with the standard access, there are moderators that can control different subreddits and there are admin that can control above what the moderators can do.

3) I would figure out what roles i would need for the system, determine which users needed which role, assign the roles to the different users and ensure that the roles are routinely checked by audits.

## WIKI - RBAC

1) Authorization is you are allowed to see the information.

2) Role assignment, Role authorization and permission authorization

3) RBAC is like a pyramid scheme. Each level you go up you gain more access to information then the previous level.

RBAC Tutorial

1) Access rights are associated with the role of the user, there can be many users that come and go but the role will stay the same meaning the access is given to the user by what role they fulfill.

2) After a user successfully authenticates themselves in the system, then they can activate access rights/Authorization.

3) RBAC might benefit a business in a few ways, since access is assigned to the role, polices don't need to be rewritten if a user leaves the organization. In addition new employees that come to the business are able to activate the given roles that they have been given by the company.
