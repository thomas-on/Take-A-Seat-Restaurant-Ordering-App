# Take-A-Seat-Restaurant-Ordering-App

In this project, the menu options were rendered using JavaScript. The HTML and CSS layout and styles were carried out based on a Figma design file.

### The JavaScript Functions
Function getMenuHtml()
Gets the menu data from external source and put it into the boilerplate and returns it.

#### Function handleAddClick()
Filters out the item from the menu array, and push it to the order list. It then calls renderOrderList().

#### Function renderOrderList()
Iterates over the order items array to render each order item and a total price to the order item display. The order item list will show a pay button if order is not yet paid.

#### Function handleRemoveClick()
Filter out those items with the paraemeter item ID from order items, and save as new array without removed item, and call renderOrderList(orderItemsArray) to render the DOM to the display.

#### Function renderPaymentModal()
Set paymentModal to flex so as to display it on the page.

#### Function closePaymentModal()
Close the paymentModal when clicked.

#### Function confirmPayment()
Renders order list informing user payment progress and, after 3 sec, calls renderOrderList(orderItemsArray) to render order list with confirmation payment message.

### Responsive Design
The app layout automatically adapts to the user screen, and was designed using a mobile-first approach. Media queries were used to adapt the layout for larger screens.

### Progressive Web Application
A web application manifest consisting of a JSON object is created to provide the app information to the browser, so that it can provide comparable user experience across multiple platforms.
