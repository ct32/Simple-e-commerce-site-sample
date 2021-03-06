# Project Name: Simple Shop
## Project Summary: This project will create a simple e-commerce site for users. 
## Github Link: https://github.com/ct32/IT202-009/tree/prod
## Project Board Link: https://github.com/ct32/IT202-009/projects/1
## Website Link: https://ct32-prod.herokuapp.com/Project/login.php
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
- Milestone 1
- Milestone 2
- Milestone 3

<table>
<tr><td>milestone 3</td></tr><tr><td>
<table>
<tr><td>F1 - User will be able to purchase items in their Cart (2021-12-10)</td></tr>
<tr><td>Status: complete</td></tr>
<tr><td>Links:<p>

 [https://ct32-prod.herokuapp.com/Project/checkout.php](https://ct32-prod.herokuapp.com/Project/checkout.php)</p></td></tr>
<tr><td>PRs:<p>

 [https://github.com/ct32/IT202-009/pull/82](https://github.com/ct32/IT202-009/pull/82)</p></td></tr>
<tr><td>
<table>
<tr><td>F1 - Create an Orders table (id, user_id, created, total_price, address, payment_method)</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905315-0903e86e-ab27-4464-acbb-c358e177e12c.png">
<p>Creating Orders Table</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145904907-66d1b9e3-e30b-4b3b-a371-7f84fd86d6ab.png">
<p>Orders Table</p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr>
<tr><td>
<table>
<tr><td>F1 - Create an OrderItems table (id, order_id, product_id, quantity, unit_price)</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905459-1140773b-4e9b-4722-96e9-dd386bbf8476.png">
<p>Creating OrderItems table</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905552-99e53579-3ad3-4460-8b36-843d934ea6c7.png">
<p>OrderItems Table</p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr>
<tr><td>
<table>
<tr><td>F1 - Checkout Form</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905815-eebf832f-195b-441a-9740-9fb4e88d0959.png">
<p>Payment method dropdown </p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905923-af3da29d-1b5f-442f-9fb6-97a85700b80e.png">
<p>Address information form</p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr>
<tr><td>
<table>
<tr><td>F1 - User will be asked for their Address for shipping purposes</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145905923-af3da29d-1b5f-442f-9fb6-97a85700b80e.png">
<p>Address information</p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr>
<tr><td>
<table>
<tr><td>F1 - Order process:</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145906470-d394d4d8-47af-453c-8ad7-3dfa7def97d7.png">
<p>Calculate Cart Items</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145906738-5d1f056c-17a0-46d2-a4c7-a7fcdadb1e07.png">
<p>Verify the current product price against the Products table (Cart unit price)</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145906938-7d32d21a-a1b3-4ad9-94f0-502ac5fd579b.png">
<p>Cart unit price from table</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/145907088-20ab49b7-fb89-4cce-8199-3497e004e7c7.png">
<p>Product unit price from table</p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/146615619-628af630-0a11-4303-a756-9ee2ab99bc52.png">
<p>Verify desired product and desired quantity are still available in the Products table</p>
 <p> Users can???t purchase more than what???s in stock</p>
</td></tr>
  


</td>
</tr>
</table>
</td>
</tr>
<table>
<tr><td>F3 - User will be able to see their Purchase History (2021-12-18)</td></tr>
<tr><td>Status: complete</td></tr>
<tr><td>Links:<p>

 [https://ct32-prod.herokuapp.com/Project/PurchaseHistory.php](https://ct32-prod.herokuapp.com/Project/PurchaseHistory.php)</p></td></tr>
<tr><td>PRs:<p>

 [https://github.com/ct32/IT202-009/pull/87](https://github.com/ct32/IT202-009/pull/87)</p></td></tr>
<tr><td>
<table>
<tr><td>F3 - For now limit to 10 most recent orders</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/009955/fff?text=completed"></td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/146720217-13f898a1-9c26-4a67-b0b4-537d79931e4f.png">
<p>user history limit to 10 </p>
</td></tr>

<tr><td>
<img width="768px" src="https://user-images.githubusercontent.com/89997131/146720698-76b54c20-4049-4b3e-a58a-39018a5f8fa5.png">
<p>shows more items in table</p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr>
<table>
<tr><td>F4 - Store Owner will be able to see all Purchase History ()</td></tr>
<tr><td>Status: pending</td></tr>
<tr><td>Links:</td></tr>
<tr><td>PRs:</td></tr>
<tr><td>
<table>
<tr><td>F4 - item 1</td></tr>
<tr><td>Status: 
<img width="100" height="20" src="https://via.placeholder.com/400x120/808080/ffffff?text=pending"></td></tr>

<tr><td>
<img width="768px" src="">
<p></p>
</td></tr>

</td>
</tr>
</table>
</td>
</tr></td></tr></table>

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
