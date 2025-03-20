# ShelfWise

## 1. Introduction
ShelfWise is an online platform designed to provide a seamless book-shopping experience. It allows users to explore a diverse collection of books, discover new reads, and manage their purchases effortlessly. The platform aims to create an intuitive and user-friendly environment, catering to both casual readers and avid book collectors.

## 2. Features
ShelfWise includes the following features:

- **User Authentication** – Secure JWT-based authentication for users, enabling account creation and login.
- **Book Browsing & Search** – Users can explore a vast collection of books, filter by genre, author, and price, and sort results for better discovery.
- **Shopping Cart & Wish List** – Users can add books to their cart for immediate purchase or save them to a wishlist for later.
- **Order Management** – Users can place, track, and manage their orders, with updates on order status.

## 3. User Interface
ShelfWise includes the following pages:

- **Home Page** – Provides an overview of the platform, with a Call-to-Action button leading to registration or login.
- **Login/Register Page** – Allows users to create an account or log in to access personalized features like shopping cart and wishlist.
- **All Books Page** – Browse the entire collection of books, search by keywords, and filter by genre, author, and price.
- **Book Preview Page** – View detailed book information, including title, author, description, and price, with options to add to cart or wishlist.
- **Shopping Cart Page** – Review selected books, manage cart items, and proceed to checkout for purchase.
- **Wishlist Page** – Save books for future purchase and move them to the shopping cart when ready.
- **My Orders Page** – View detailed information about the user’s previous orders and their progress.

![image](images/sitemap.png)

## 4. Functionality

### 4.1. Home Page
The **Home Page** provides a brief overview of the web application, with an emphasis on guiding users toward registration or login.

#### Components on the Home Page:
- **Call-to-Action button** – Directs users to the **Login/Register Page**.
- **Basic demo of the platform** – A preview of how ShelfWise works, but without search or filtering functionalities.

![image](images/home-page-1.jpg)
![image](images/home-page-2.jpg)
![image](images/home-page-3.jpg)

### 4.2. Login/Register Page
The **Login/Register Page** allows users to authenticate and gain access to personalized features.

#### Elements on the page:
- **Login form** – Users enter their credentials to sign in.
- **Register form** – Users create an account by providing their details.
- **Forgot password option** – Allows users to reset their password if needed.

![image](images/login-page.jpg)
![image](images/register-page.jpg)

#### Navigation from this page:
- **Back to Home Page**
- **Navigate to All Books Page** after successful login.

### 4.3. All Books Page
The **All Books Page** enables users to browse the complete collection of books available on the platform.

#### Elements on the page:
- **Search bar** – Allows users to search for books by title, author, or keywords.
- **Filters and sorting options** – Users can filter books by genre, author, and price.
- **Book list/grid** – Displays all books with a preview of the title, author, and price.
- **Pagination** – If there are many books, the list is divided into pages for easier navigation.
- **Click on a book** – Redirects users to the **Book Preview Page** for more details.

![image](images/all-books-page.jpg)

#### Navigation from this page:
- **Back to Home Page**
- **Navigate to Book Preview Page** when a book is selected.

### 4.4. Book Preview Page
The **Book Preview Page** opens when a user clicks on a book. This page displays detailed information about the selected book.

#### Elements on the page:
- **Book title and author**
- **Book description**
- **Book price** (if available for purchase)
- **"Add to Cart" button** – Allows the user to add the book to their shopping cart.
- **"Add to Wishlist" button** – Enables the user to save the book for later.

![image](images/book-preview-page.jpg)

#### Navigation from this page:
- **Back to All Books Page**
- **Navigate to Shopping Cart Page** if the user adds a book to their cart.
- **Navigate to Wishlist Page** if the user saves a book.

### 4.5. Shopping Cart Page
The **Shopping Cart Page** allows users to review and manage the books they have added to their cart.

#### Elements on the page:
- **List of books in the cart**, displaying title, author, and price.
- **Remove button** – Allows users to remove a book from the cart.
- **Total order amount** – Displays the total price of books in the cart.
- **"Proceed to Checkout" button** – Redirects the user to the **Order Management Page**.

![image](images/shopping-cart-page.jpg)

#### Navigation from this page:
- **Back to Book Preview Page**
- **Back to All Books Page**
- **Navigate to Order Management Page**.

### 4.6. Wishlist Page
The **Wishlist Page** allows users to save books for later purchase.

#### Elements on the page:
- **List of saved books**, displaying title and author.
- **"Move to Cart" button** – Moves a book from the Wishlist to the Shopping Cart.
- **Remove button** – Allows users to remove a book from the Wishlist.

![image](images/wishlist.jpg)

#### Navigation from this page:
- **Back to All Books Page**
- **Navigate to Shopping Cart Page**.

### 4.7. Order Management Page
The **Order Management Page** allows users to complete their purchases and track their orders.

#### Elements on the page:
- **Customer details form** – Fields for name, surname, address, and payment method.
- **Order summary** – Displays total price and list of books.
- **"Confirm Order" button** – Completes the purchase.
- **Order history list** – Shows the status of previous orders (e.g., "Shipped", "Delivered").

![image](images/order-page-1.jpg)
![image](images/order-page-2.jpg) 
![image](images/my-orders-page.jpg)

#### Navigation from this page:
- **Back to Shopping Cart Page**
- **Back to All Books Page**.
