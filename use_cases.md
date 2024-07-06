# Use cases for **CodeVault**

## Version 1

- [ ] **Creating a user**: User creates an account using the registration form. After validation, the data is populated in the *User* table.
- [ ] **View User profile**: Profile page displays user information from *User* table and associated projects from *Project* table.
- [ ] **Deleting Account**: User deletes account using a button. What happens to the projects if he/she is the only associated user?
- [ ] **Login successful or unsuccessful**: User provides login credentials using the login form. The credientials are checked using the *User* table.
- [ ] **Creating a Project**: Users can create a private project and the data is populated in the *Project* table.
- [ ] **Viewing all the projects**: An user can view the projects he/she associated with on the projects page.
- [ ] **Delete a project**: *Owner* of the project can delete a project using a button.
- [ ] **Inviting a collabortor**: An *Owner* of a project can invite users as a collaborator. Collaborators have *read* and *write* permission on the project(This will change in the 1.1 version). First, it checks if the user is registered using the *User* table. Secondly, it adds the user as a *collaborator* in the *Project* table.
- [ ] **Downloading a project**: A project is downloaded using a button in the project page.
- [ ] **Viewing project files**: Project files are listed in the project page of according to the branch. *main* or *master* branch is selected by default. Project info is retreived from the *Project* table.
- [ ] **Project branches**: Project branches are listed in the dropdown menu in the project page.
- [ ] **Commit History**: git commits are listed in the *Commits* pages according to the branch. *main* or *master* branch is selected by default.

## Version 1.1

- [ ] **Public projects**: Users can create a public projects. In a public projects every user is a *collaborator* with only the *read* permission unlike the *Owner*.
- [ ] **Project permission change**: For both public and private projects, *Owner* has *read* and *write* permission wheres *Collaborator* has only *read* permission.
- [ ] **Pull request**: Collaborators can create pull request to include their commits to the project. *Owner*s can accept or reject pull requests.
- [ ] **Creating an organization**: An user can create an organization. The user will be the *owner* of the organization.
- [ ] **Inviting people in a orgnization**: An *Owner* of an organization can invite other users as *Member*s. A *Member* has *write* and *read* permission on projects under the organization.
- [ ] **Creating a project under organization**: *Owner* of the organization can create a project under it. It can be a private or public project. It's *Member*s has *write* and *read* permission on projects under it.
- [ ] **Searching**: Users can search public projects, organizations, and users using a search bar.
