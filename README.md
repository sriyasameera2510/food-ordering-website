# Food Ordering Website

## Description

This is a full-stack food ordering website built with React.js, MongoDB, and Tailwind CSS. The website allows users to browse through a menu, customize their orders, add items to the cart, and make secure payments using Stripe. Users can register, login, view their order history, and update their profile information. Admin users have additional functionalities to manage categories, menu items, users, and orders.

## Features

### Homepage
- **Navigation Bar:** A top navigation bar with menu items (Home, Menu, About Us, Contact Us, Register, Login, Cart).
- **Best Seller Items:** Displays a selection of popular or best-selling items from the menu.

### Menu Page
- **Menu Items:** Lists all menu items fetched from the database, categorized by type (e.g., Appetizers, Main Courses, Desserts).
- **Item Customization:** Allows users to customize items by selecting size, choosing extra ingredients (e.g., cheese, pepperoni), and adding special instructions.

### Cart Page
- **Cart Summary:** Displays all items added to the cart, along with their prices and quantities.
- **Address Input:** Provides a form for users to input their delivery address.
- **Order Summary:** Shows the total order amount and provides a button to proceed to checkout.

### Checkout Page
- **Secure Payments:** Integrates with Stripe for secure payment processing.
- **Payment Form:** Allows users to enter their payment details (credit card information).
- **Order Confirmation:** Displays a confirmation message and order details after successful payment.

### User Authentication
- **User Registration:** Allows new users to create an account by providing their name, email, and password.
- **User Login:** Existing users can log in using their email and password.
- **Google Login:** Users can also log in using their Google account for convenience.

### User Profile
- **Profile Information:** Displays user's name, email, address, and profile image.
- **Edit Profile:** Allows users to edit their profile information, including changing their password.
- **Order History:** Shows a list of previous orders with details such as order date, items ordered, and total amount.

### Admin Panel
- **Category Management:** Admin can add, edit, and delete categories (e.g., Pasta, Pizza, Drinks) for menu items.
- **Menu Item Management:** Admin can add, edit, and delete menu items, including setting prices and descriptions.
- **User Management:** Admin can view a list of all users, edit their information, and promote users to admin status.
- **Order Management:** Admin can view a list of all orders, including details such as order date, items ordered, total amount, and user information.

## Technologies Used

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment:** Stripe
