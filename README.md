# python-challenge-1

# Welcome to Chef Geoff's Food Truck Receipt Printer!

## Please run the menu.py file
You will be prompted for entries to select menu items at Chef Geoff's Food Truck. Based on your selections, you will receive a printout of your order and the total cost.

# _Code Process_
### Menu dictionary established and customer order begins

### 1. Set up order list. Order list will store a list of dictionaries for menu item name, item price, and quantity ordered

- Launch the store and present a greeting to the customer
- Customers may want to order multiple items, so let's create a continuous loop
- Ask the customer from which menu category they want to order
- Create a variable for the menu item number
- Create a dictionary to store the menu for later retrieval
- Print the options to choose from menu headings (all the first level dictionary items in menu).
- Store the menu category associated with its menu item number
- Add 1 to the menu item number
- Get the customer's input
- Check if the customer's input is a number
- Check if the customer's input is a valid option
- Save the menu category name to a variable
- Print out the menu category name they selected
- Print out the menu options from the menu_category_name
- Check if the menu item is a dictionary to handle differently

### 2. Ask customer to input menu item number
### 3. Check if the customer typed a number
- Convert the menu selection to an integer
### 4. Check if the menu selection is in the menu items
- Store the item name as a variable
- Ask the customer for the quantity of the menu item
- Check if the quantity is a number, default to 1 if not
- Tell the customer that their input isn't valid
- Add the item name, price, and quantity to the order list
- Tell the customer they didn't select a menu option
- Otherwise, tell the customer they didn't select a number
- Ask the customer if they would like to order anything else
### 5. Check the customer's input using a match-case statement

### __Print out the customer's order__

### 6. Loop through the items in the customer's order
### 7. Store the dictionary items as variables
### 8. Calculate the number of spaces for formatted printing
### 9. Create space strings
### 10. Print the item name, price, and quantity
### 11. Calculate the cost of the order using list comprehension
- Multiply the price by quantity for each item in the order list, then sum() and print the prices.

# Don't forget to leave a tip and...Enjoy your food!