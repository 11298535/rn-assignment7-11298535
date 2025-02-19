# rn-assignment7-11298535

rn-assignment7-11298535 project

React Native Shopping App

This is a React Native shopping app that showcases a product list and a shopping cart functionality. The app fetches product data from an API, displays products in a grid, and allows users to add products to their cart. The cart data is persisted using AsyncStorage.

Features
Home Screen: Displays a list of products fetched from the API.

Product Details Screen: Shows detailed information about a selected product.

Cart Screen: Displays the products added to the cart and allows users to remove items.

Persistent Cart: Uses AsyncStorage to persist cart data between app sessions.

Filter Menu: Allows users to filter products by category (sample filter categories included).

Navigation: Navigate between Home, Product Details, and Cart screens.

Design Choices
User Interface
Grid Layout: The Home screen uses a grid layout to display products, making efficient use of screen space and providing a visually appealing interface.

Product Cards: Each product is displayed as a card with an image, title, category, price, and description. The "Add to Cart" icon is prominently placed to facilitate easy addition to the cart.

Navigation Icons: Included navigation icons to allow users to move between screens easily.

Data Fetching
API Integration: Used axios to fetch product data from a sample API. This demonstrates how to integrate external data sources into the app.

Data Storage
AsyncStorage: Implemented AsyncStorage to persist cart data. This ensures that the cart contents are saved even if the app is closed or the device is restarted.

Implementation Details
Screens and Navigation
Home Screen: Displays a list of products in a grid. Each product can be clicked to navigate to the Product Details screen. A button to view the cart navigates to the Cart screen.
Product Details Screen: Shows detailed information about the selected product, including an option to add the product to the cart.
Cart Screen: Displays the items added to the cart, along with their details and the total price. Users can remove items from the cart.
Adding and Removing Items from Cart
Add to Cart: When a user clicks the "Add to Cart" icon on a product card or the "Add to Basket" button on the Product Details screen, the product is added to the cart. The cart is then saved to AsyncStorage.
Remove from Cart: Users can remove items from the cart by clicking the remove icon. The cart is updated and saved to AsyncStorage.
Persisting Cart Data
Loading Cart: When the app initializes, it loads the cart data from AsyncStorage to maintain the user's cart across sessions.
Saving Cart: Whenever the cart is updated (item added or removed), the new cart state is saved to AsyncStorage.


Conclusion:
This app provides a basic structure for a Shopping application with product listing, detailed product view, and cart functionality. It demonstrates how to fetch data from an API, manage state with React hooks, and persist data using AsyncStorage. The design focuses on a clean and intuitive user experience, with easy navigation and seamless cart management.# rn-assignment7-11298535
![cartpage](https://github.com/user-attachments/assets/bba37f93-930a-450a-9f51-c5542cb87a49)
![homepage](https://github.com/user-attachments/assets/f9681bcd-a699-4ade-bd66-8e3cc57984fc)
![homepage1](https://github.com/user-attachments/assets/369b4157-271a-4044-9c51-2c038b37f9eb)
![productdetails](https://github.com/user-attachments/assets/0911ff7f-1903-46e8-9f7a-c62355e8b84c)
![productdetails1](https://github.com/user-attachments/assets/8e45f534-a86f-40e6-91eb-bc65bfbfad86)
