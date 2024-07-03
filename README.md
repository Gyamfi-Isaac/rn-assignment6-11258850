# rn-assignment6-11258850
## Overview
This React Native project implements a shopping app with two main screens: HomeScreen for viewing available products and CartScreen for managing the cart. The app utilizes useContext for state management and AsyncStorage for local data storage.

## Design Choices
* Context API: Used for managing the cart state across different components, making it easier to add and remove items from the cart without prop drilling.
* AsyncStorage: Chosen for local data storage to persist cart items even when the app is closed or restarted.
* FlatList: Utilized for efficient rendering of the product and cart item lists, ensuring smooth performance even with a large number of items.
* Modular Components: Separate components for ProductCard and context management to keep the codebase organized and maintainable.

## Implementation
* Cart Context: A CartContext provides methods to add and remove items from the cart. The cart state is persisted using AsyncStorage.
* HomeScreen: Displays a list of available products with an "Add to Cart" button for each product.
* CartScreen: Displays the items in the cart with a "Remove from Cart" button for each item.
* Data Storage: AsyncStorage is used to save and load cart items to ensure the cart state is preserved across app sessions.

## Screenshots

![Screenshort-1](https://github.com/Gyamfi-Isaac/rn-assignment6-11258850/assets/170130824/6dc70038-b956-4dfe-bed5-60bd2ba706fc)

![Screenshot-2](https://github.com/Gyamfi-Isaac/rn-assignment6-11258850/assets/170130824/4cedc10c-334c-44b6-8dc4-39640d1b4f86)

![Screenshot-3](https://github.com/Gyamfi-Isaac/rn-assignment6-11258850/assets/170130824/5682ba83-83c5-456c-8e4a-20645760aace)




