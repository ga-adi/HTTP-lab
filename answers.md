Login page for E-Z Swords web store:
* page has inputs for username & password and a Login button
* on click of Login button - send POST request including username and encrypted password as data

User is taken to the Browse Weapons page:
* page shows a list of available items w/ picture & price
* on scroll to bottom - sent GET request for more items and add them to grid view
* click on an item - send GET request including product ID in the query string

User is taken to the Weapon Detail page:
* page has a picture of item, item title, rating bar (1 to 4 stars), and "Add to Armory" button (shopping cart)
* on click of rating bar - send POST request including product ID and rating - rating is saved in the database on the server and associated with the product; user stays on the product detail page
* on click of "Add to Armory" button - send POST request inluding item ID - item is saved in the user's shopping cart on the database

After clicking "Add to Armory" user is taken to the Armory/checkout page:
* page has a list of items the user added to their Armory and a Checkout button
* on click of Checkout button - send Post request including the list of items in the shopping cart

After checkout, user is taken to the order confirmation page:
* page shows a confirmation/order # and a "Arm more troops" button
* on click of button, send GET request that asks for the "browse weapons" page and takes user back there
