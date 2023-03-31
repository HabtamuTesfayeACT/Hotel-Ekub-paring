# Hotel/Ekub-paring
 # Ekub,Hotel Menu and Parking web

## Introduction

Welcome to my web! I am excited to have you here and hope you enjoy your browsing experience. In this README blog, we will provide you with information on what you can expect to find on our web, how to navigate it, and some of the key features that we offer.

## **Getting Started:**

To start browsing our web, simply type[https://habtamutesfayeact.github.io/Hotel-Ekub-paring/](https://habtamutesfayeact.github.io/Hotel-Ekub-paring/) or click on the link above. Once you arrive on our homepage, you will be greeted with a clean, simple design that is easy to navigate. Our homepage features a menu bar at the top, which provides links to all of the different sections of the web like ekub page ,Hotel menu page and Parking page

## Navigation

To navigate our web, simply click on any of the links in the menu bar at the top of the page. Once you arrive on a new page, you will find that our web is designed to be easy to read with each functionality is displayed in one page side by side

## How does it work

T**he First Ekub.html** 

there is an HTML document with inline CSS and JavaScript code. It contains a navigation bar, a form to register for an event, and a table to display the registered participants. The table also includes a feature that randomly selects a winner from the registered participants.

The JavaScript code defines variables for the form inputs and the table, as well as arrays to store the registered participants and their amounts. It also includes a function to add a new row to the table with the entered name and amount, as well as to update the total sum and select a winner randomly from the registered participants. The function is called when the "Register" button is clicked.

This is a JavaScript function called "createTable". Here's what it does:

1. It updates the total sum of entered amounts and displays it in the "sum" table row.
2. It sets the "Random" table row to display the selected winner.
3. It generates a random index using the "emp" array length, and stores the corresponding name in a separate array called "sname".
4. It adds the entered amount to an array called "emp" at the current index, and increments the index.
5. It creates a new row in the table, and inserts three cells into it: one for the row number, one for the entered name, and one for the entered amount.
6. It gets references to various elements in the HTML document, including the "name" and "amount" form fields, the "sum" and "Random" table rows, and the "mytable" table.
7. It checks if the "name" and "amount" form fields are filled out. If either one is empty, it displays an alert message and returns false, preventing the form from submitting.

T**he second Hotel.html**

This is an HTML file that displays a form for adding food items to a menu and a table that shows the list of food items with their ingredients and prices. The table also has a remove button for each row.

The JavaScript code handles adding new rows to the table when the form is submitted, and also includes the functionality for the remove button for each row. There are also some basic form validation checks to ensure that the user has filled out all required fields before submitting the form.

This is JavaScript code that adds a new row to a table when a user submits a form on a webpage. The code does the following:

1. It retrieves the input values for the food name, ingredient, and price from the form.
2. It checks to make sure that all the input fields are filled out. If not, it displays an alert message.
3. It gets a reference to the table in the HTML document and inserts a new row into it.
4. It assigns an ID to the new row based on the number of rows already in the table.
5. It inserts four cells into the new row, and populates them with the input values for the food name, ingredient, and price, and a "remove" button.
6. It creates the "remove" button as an HTML input element, sets its type to "button", and adds an onclick handler to it that removes the entire row from the table when clicked.
7. It appends the "remove" button to the last cell in the row.

This code assumes that there is an HTML table on the page with an ID of "mytable", and that there is a form with ID "RegForm" containing input fields for the food name, ingredient, and price.

The HTML code you provided creates a page with a registration form for parking and a table to display the registered vehicles. The JavaScript code handles the form submission and dynamically adds new rows to the table to display the registered vehicles.

The JavaScript code also calculates the parking time and payment for each vehicle based on the time of registration and the time of removal. When the "remove" button is clicked for a row, the row is removed from the table and an alert is displayed showing the payment due for the parking duration of the removed vehicle.

This JavaScript code defines a function called **`createTable()`** which is triggered by clicking the "Register" button in an HTML form. The function does the following:

1. It checks if the Plate and Model fields in the form are filled. If either of them is not filled, an alert message is displayed and the function returns false.
2. It gets the current date and time and creates a new row in a table with an id of "mytable". The row contains four cells: one for a serial number, one for the Plate number, one for the Model, and one for the time of registration.
3. It calculates the time of registration in minutes and stores it in the third cell of the new row.
4. It creates a "remove" button in the fourth cell of the new row, with an onclick event that removes the row from the table and calculates the payment based on the time of registration and the current time.

The function uses the **`getElementById()`** method to get references to the Plate and Model input fields, and to the "mytable" table. It also uses a counter variable **`counter1`** to keep track of the serial number of each registration

## Conclusion

We hope that this README blog has been helpful in providing you with an overview of our web and what you can expect to find here. If you have any questions or feedback, please don't hesitate to get in touch with us. We are always happy to hear from our visitors and are committed to providing you with the best browsing experience possible. Thanks for visiting our web, and we look forward to seeing you again soon!
