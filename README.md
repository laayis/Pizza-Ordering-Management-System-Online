My First Java Web Application
______________________________



Basic Java Based Application to handle Pizza Orders.


Customer End:
---------------
1) Customer can place orders.
2) Customer can track their past Orders.


For Option: Create new order
+++++++++++++++++++++++++++++

On creating a new order this system generates an unique order id. Customes uses that id to
track the placed order in future.
Once the id is generated and displayed to the user, he/she will be shown a menu, a
short one containing about 4 varieties of pizzas with 3 sizes available. Add appropriate check
boxes for the user to select the item and a field to input the quantity of each(set default to 1
which would be considered only if the checkbox is checked). It would be even better if you
can add images for every item.
On submit your order, the webpage navigates to another form asking the user to enter
his name, contact number and address as mandatory fields.
This System is maintaining sessions(maintain order id and selected items) while the previous page
navigates to this page and display your order id on the top of the page.
On entering the personal details the user will be able to navigate to the tracking page of
his/her order indicating the progress till Order Placed.
States possible(transition possible in the same order): Order Placed, Preparation, Bake,
Quality Check, Out for delivery, Delivered.

For Option: Track my order
+++++++++++++++++++++++++++
Customer should be prompted to enter the order id. On submitting it, the webpage
displaying the progress with the stage should be displayed.


Restaurant view:
----------------------------
The user should be able to view all the pending(undelivered) orders and their state in
tabular form, with an update button corresponding to each row.




How to run this application
--------------------------
You need to compile and run customer_1.jsp file and Restaurant.jsp file

