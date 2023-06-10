# Class 08 Reading: Access Control (ACL)

## Resources

- [5 Steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)
- [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)
- [RBAC Tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

## 5 Steps to RBAC

1. What is Role Based Access Control and why do we care?
    - Role Based Access Control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.
    - A role hierarchy is a mechanism for subordinating roles to other roles, in a parent-child relationship. The role hierarchy can be up to 500 roles deep. The role hierarchy makes it easier to assign users to the appropriate roles, because you can assign a user to a role at or above the user's own role in the hierarchy.

3. What approach might you take to implement RBAC?
    - The RBAC approach is to assign permissions to specific roles in an organization and then assign those roles to users. In this way, roles become a way to group permissions together logically. Users can then be assigned to roles, instead of having permissions assigned to them directly.

## wiki - RBAC

1. If Authentication is "you are who you say you are," what is authorization?
    - Authorization is "you can do what you say you can do."

2. Name three primary rules defined for RBAC:
    - Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
    - Role authorization: A subject's active role must be authorized for the subject.
    - Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role.

3. Describe RBAC to a non-technical friend:
    - RBAC is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.

## RBAC Tutorial

1. What are access rights associated with? The User or Role?
    - Access rights are associated with roles.
    - Roles are then assigned to users.

2. Access rights, or authorization, is activated after a user successfully does what?
    - Authentication is activated after a user successfully logs in.

3. Explain how RBAC might benefit a business:
    - RBAC can help a business efficiently manage permissions as employees join, change teams, or leave the company.

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-08/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: Implement RBAC into a project of mine. Maybe I can add it to my portfolio project.

#### Things I Want to Know More About

1. Question 1?
    - Answer 1.

![GIF](https://media.giphy.com/media/3o6ZsUfMW2CVnzsCnC/giphy.gif)
