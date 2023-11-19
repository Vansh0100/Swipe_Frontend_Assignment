# Swipe_Frontend_Assignment

# Setting up the project
- To install all the dependencies use ```npm install```
- To start the project use ```npm start```

# Code Flow
- On the landing page I have made a button named as Edit Invoices on clicking which a modal will appear that will allow the users to select the invoices that needed to be edited in bulk.
- On the same modal, there is a button Delete Selected Items provided for deleting the selected invoices from the available invoice list.
- Then on selecting the invoices that needed to be edited in bulk, user will click on the button Edit Selected Items which will navigate the user to a different route ```http://localhost:3000/bulkEdit``` on which user can edit the invoice in bulk.
- And in each invoice there is a button associated with each invoice which on clicking opens a modal and displays the items associated with that invoice.
- And in each modal there is a option to edit the items in bulk as well as user can delete and add new item accordingly.
- And on clicking Update Item List button the modal will be closed.
- And when user clicks on Save Edit Changes button, user will be redirected to the main page with the updated invoice list.
- I have created a function to create random invoices for displaying it initially on the landing page.
