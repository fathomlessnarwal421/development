# Development

### Link to Deployed Website
If you used the stencil code, this is `https://fathomlessnarwal421.github.io/development`

### Goal and Value of the Application
The goal of this application was to create a website for users to shop for clothing items. The user is able to add and remove items from their cart, and their cart will display and keep track of the price the user is at. The user is also able to filter their items by the different categories available, which are tops, bottoms, and accessories. The user can also sort the items by featured items, price, or rating. The application makes it quick and easy for the user to pick out clothing items they need by filtering and sorting, and track their total spending price. 

### Usability Principles Considered
The layout prioritizes the clothing items in the center of the screen. The cart is displayed on the right and is always displayed on the screen so the user can track their total price. The filter and sort options are on the left of the clothing items and grouped together to make finding all these options more intuitive. All the buttons look the same so that the user will be able to understand what parts of the screen are buttons. Different font weights are used to indicate hierarchy in the text, like for the shop name or the titles of the clothing items. The design maintains a minimalist design with only a few chosen colors to keep the website as intuitive and easy to use as possible. 

### Organization of Components
The state variables used were clothesItems, sortBy, type, price, cartItems, and cartData. Both sortBy and type are variables that keep track of the filtering and sorting option that the user has selected. The cart component uses price, cartItems, and cartData to keep track of what should be displayed in the cart. The 2 components used were a Menu component for each menu item and a Cart component to display the cart data. 

### How Data is Passed Down Through Components
The items in clothesItems are passed to the Menu component and displayed from there. The props that the Menu component takes in are the item and a button for the addToCart function.  Similarly, the price, cartData, cartItems, and 2 button variables are passed to the Cart component as props and displayed from there. 

### How the User Triggers State Changes
The user triggers state changes by changing the options on the sort by drop down or the filtering buttons. These will change the state of clothesItems and filter or sort accordingly depending on the options selected. The user also triggers state changes by clicking the add to cart button or clicking the + - buttons in the cart to change the number of the items in the cart. This updates the cart items as well as the price. 

