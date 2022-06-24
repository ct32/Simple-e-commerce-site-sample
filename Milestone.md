
# Project Name: Simple Shop
## Project Summary: This project will create a simple e-commerce site for users. 
## Github Link: (Prod Branch of Project Folder)
## Project Board Link: 
## Website Link: (Heroku Prod of Project folder)
## Your Name: Caterine Tapia

<!--
### Line item / Feature template (use this for each bullet point)
#### Don't delete this

- [ ] \(mm/dd/yyyy of completion) Feature Title (from the proposal bullet point, if it's a sub-point indent it properly)
  -  List of Evidence of Feature Completion
    - Status: Pending (Completed, Partially working, Incomplete, Pending)
    - Direct Link: (Direct link to the file or files in heroku prod for quick testing (even if it's a protected page))
    - Pull Requests
      - PR link #1 (repeat as necessary)
    - Screenshots
      - Screenshot #1 (paste the image so it uploads to github) (repeat as necessary)
        - Screenshot #1 description explaining what you're trying to show
### End Line item / Feature Template
--> 
### Proposal Checklist and Evidence

**Milestone 1**
- [x] \(11/06/2021) User will be able to register a new account
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/register.php
    - Pull Requests
      - https://github.com/ct32/IT202-009/pull/7
    - Screenshots
        
        ![image](https://user-images.githubusercontent.com/89997131/140630985-0c463a77-c0f0-48e0-a071-be8cec77e8b0.png)
        - Screenshot #1 shows the registration requirements for the user (form fields)
        
        ![image](https://user-images.githubusercontent.com/89997131/140631051-2975afa0-41e8-4b30-bba4-0c9bc7d3048c.png)
        - Screenshot #2 shows a user that has successfully registered
        
        ![image](https://user-images.githubusercontent.com/89997131/140631229-47750891-348f-4b93-ab12-0e210ef3b399.png)
        - Screenshot #3 shows users table

  - Form Fields
      - Username, email, password, confirm password (other fields optional)
      - Email is required and must be validated
      - Username is required
      - Confirm password’s match
  - Users Table
      - Id, username, email, password (60 characters), created, modified
  - Password must be hashed (plain text passwords will lose points)
  - Email should be unique
  - Username should be unique
  - System should let user know if username or email is taken and allow the user to correct the error without wiping/clearing the form
      - The only fields that may be cleared are the password fields

- [x] \(11/06/2011) User will be able to login to their account (given they enter the correct credentials)
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/login.php

    - Pull Requests
      - https://github.com/ct32/IT202-009/pull/7
    - Screenshots
    
      ![image](https://user-images.githubusercontent.com/89997131/140631496-25370353-fb96-48ab-b153-ad90f4076008.png)
      - Screenshot #1 shows login page before user logs in
      
      ![image](https://user-images.githubusercontent.com/89997131/140631520-5f4cb6b2-c187-4792-9f81-aa073a1f644e.png)
      - Screenshot #2 shows a successful login with email
      
      ![image](https://user-images.githubusercontent.com/89997131/140631570-11cfcb9b-3e39-4a9b-ab3d-05e8b24b3770.png)
      - Screenshot #3 shows a successful login with username

   - Form
      - User can login with email or username
          - This can be done as a single field or as two separate fields
      - Password is required
  - User should see friendly error messages when an account either doesn’t exist or if passwords don’t match
  - Logging in should fetch the user’s details (and roles) and save them into the session.
  - User will be directed to a landing page upon login
      - This is a protected page (non-logged in users shouldn’t have access)
      - This can be home, profile, a dashboard, etc

- [x] \(11/06/2021) User will be able to logout
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/login.php
    - Pull Requests
      - https://github.com/ct32/IT202-009/pull/7
    - Screenshots
      
      ![image](https://user-images.githubusercontent.com/89997131/140631856-f6fae111-2bd1-4866-aec7-f00b6c8f047b.png)
        - Screenshot #1 shows a successful log out and redirected back to login page
       ![image](https://user-images.githubusercontent.com/89997131/140788625-7867ccc2-6e39-4237-a458-0458fc053764.png)
        - Screenshot #2 shows it does not allow access with back button once logged out

  - Logging out will redirect to login page
  - User should see a message that they’ve successfully logged out
  - Session should be destroyed (so the back button doesn’t allow them access back in)

- [x] \(11/08/2021) Basic security rules implemented
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/login.php
    - Pull Requests
      - https://github.com/ct32/IT202-009/pull/7
    - Screenshots
    
        ![image](https://user-images.githubusercontent.com/89997131/140800896-a82ca188-6aca-49d8-8a44-6efc08caee4b.png)
        - Screenshot #1 function to check if user is logged in

      ![image](https://user-images.githubusercontent.com/89997131/140791308-45522ac3-cfcf-4b0b-8c52-a97d0c8a926c.png)
      ![image](https://user-images.githubusercontent.com/89997131/140818025-ac038f79-23dd-411d-b46e-893c6d75c855.png)

      ![image](https://user-images.githubusercontent.com/89997131/140792465-0fdc7ca7-b615-4389-861f-d6c0e72a5186.png)

        - Screenshot #2 and 3 show functions called on appropriate pages
     
  - Authentication:
      - Function to check if user is logged in
      - Function should be called on appropriate pages that only allow logged in users
  - Roles/Authorization:
      - Have a roles table (see below)

- [x] \(11/08/2021) Basic Roles implemented
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/login.php
    - Pull Requests
      https://github.com/ct32/IT202-009/pull/20
    - Screenshots
    
      ![image](https://user-images.githubusercontent.com/89997131/140792918-7580b76f-b8fa-4a26-93a9-755ec3cc8453.png)
        - Screenshot #1 shows roles table
       ![image](https://user-images.githubusercontent.com/89997131/140793099-a4cc2787-534d-4240-81ce-2597f4d99859.png)
        - Screenshot #2 shows user roles table
       ![image](https://user-images.githubusercontent.com/89997131/140793290-4c05b3fe-5a90-4baf-a174-c1a84d0f0894.png)
        - Screenshot #2 function to check if a user has a specific role


  - Have a Roles table	(id, name, description, is_active, modified, created)
  - Have a User Roles table (id, user_id, role_id, is_active, created, modified)
  - Include a function to check if a user has a specific role (we won’t use it for this milestone but it should be usable in the future)
 
- [x] \(11/08/2021) Site should have basic styles/theme applied; everything should be styled
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/home.php
    - Pull Requests
      - https://github.com/ct32/IT202-009/pull/7
    - Screenshots
    - 
      ![image](https://user-images.githubusercontent.com/89997131/140801108-2b594827-24c9-44e9-a5f8-5ea840854199.png)
        - Screenshot #1 shows navigation bar 
  - I.e., forms/input, navigation bar, etc

- [x] \(11/08/2021) Any output messages/errors should be “user friendly”
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/login.php
    - Pull Requests
      https://github.com/ct32/IT202-009/pull/8
    - Screenshots
    
      ![image](https://user-images.githubusercontent.com/89997131/140801931-b17c5b56-2dd9-4a04-8ce0-007d204eeb8b.png)
        - Screenshot #1 shows message to user if they enter the wrong password
       ![flashmessage](https://user-images.githubusercontent.com/89997131/140802105-1d3bfaaa-1350-4f42-9c49-4db06faf0bd7.PNG)
        - Screenshot #2 shows message to user enter a password that is too short

  - Any technical errors or debug output displayed will result in a loss of points

- [x] \(11/08/2021) User will be able to see their profile
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/profile.php
    - Pull Requests
      https://github.com/ct32/IT202-009/pull/29
    - Screenshots
    
      ![image](https://user-images.githubusercontent.com/89997131/140802516-0a9293e9-dcf7-4f0b-a5b7-cac5eb387bee.png)
        - Screenshot #1 shows user's profile information
  - Email, username, etc

- [x] \(11/08/2021) User will be able to edit their profile
  -  List of Evidence of Feature Completion
    - Status: Completed
    - Direct Link: https://ct32-prod.herokuapp.com/Project/profile.php
    - Pull Requests
      https://github.com/ct32/IT202-009/pull/29
    - Screenshots
      ![image](https://user-images.githubusercontent.com/89997131/140816493-766114a8-60a9-4059-a82e-710f2a640bb2.png)
        - Screenshot #1 shows changing the username
      ![image](https://user-images.githubusercontent.com/89997131/140816632-cf977640-e6bc-4450-bd15-7ad143046b4b.png)
        - Screenshot #2 shows successful log in with new username

  - Changing username/email should properly check to see if it’s available before allowing the change
  - Any other fields should be properly validated
  -Allow password reset (only if the existing correct password is provided)
       - Hint: logic for the password check would be similar to login


- Milestone 2
- Milestone 3
- Milestone 4
### Intructions
#### Don't delete this
1. Pick one project type
2. Create a proposal.md file in the root of your project directory of your GitHub repository
3. Copy the contents of the Google Doc into this readme file
4. Convert the list items to markdown checkboxes (apply any other markdown for organizational purposes)
5. Create a new Project Board on GitHub
   - Choose the Automated Kanban Board Template
   - For each major line item (or sub line item if applicable) create a GitHub issue
   - The title should be the line item text
   - The first comment should be the acceptance criteria (i.e., what you need to accomplish for it to be "complete")
   - Leave these in "to do" status until you start working on them
   - Assign each issue to your Project Board (the right-side panel)
   - Assign each issue to yourself (the right-side panel)
6. As you work
  1. As you work on features, create separate branches for the code in the style of Feature-ShortDescription (using the Milestone branch as the source)
  2. Add, commit, push the related file changes to this branch
  3. Add evidence to the PR (Feat to Milestone) conversation view comments showing the feature being implemented
     - Screenshot(s) of the site view (make sure they clearly show the feature)
     - Screenshot of the database data if applicable
     - Describe each screenshot to specify exactly what's being shown
     - A code snippet screenshot or reference via GitHub markdown may be used as an alternative for evidence that can't be captured on the screen
  4. Update the checklist of the proposal.md file for each feature this is completing (ideally should be 1 branch/pull request per feature, but some cases may have multiple)
    - Basically add an x to the checkbox markdown along with a date after
      - (i.e.,   - [x] (mm/dd/yy) ....) See Template above
    - Add the pull request link as a new indented line for each line item being completed
    - Attach any related issue items on the right-side panel
  5. Merge the Feature Branch into your Milestone branch (this should close the pull request and the attached issues)
    - Merge the Milestone branch into dev, then dev into prod as needed
    - Last two steps are mostly for getting it to prod for delivery of the assignment 
  7. If the attached issues don't close wait until the next step
  8. Merge the updated dev branch into your production branch via a pull request
  9. Close any related issues that didn't auto close
    - You can edit the dropdown on the issue or drag/drop it to the proper column on the project board
