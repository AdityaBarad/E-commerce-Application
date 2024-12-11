# E-Commerce Application

This E-Commerce Application is developed using Flutter, designed to provide users with a seamless shopping experience. It includes functionalities like product browsing, detailed product views, search and sort options, user authentication, and a robust cart system with checkout capabilities.

## Features

### Homepage
- Displays a list of featured products, each showing an image, name, price, and ratings.
- Initially loads 10 products with infinite scrolling to fetch additional items as the user scrolls down.

### Product Detail Page
- Displays detailed information about a selected product.
- Information includes:
  - Product images
  - Name
  - Price
  - Description
  - Ratings
  - Reviews

### Product Search Functionality
- Allows users to search for products by typing their names.
- Displays search results with:
  - Product image
  - Name
  - Price
  - Rating

### User Authentication
- Features login and logout functionality.
- Validates user registration details:
  - Name
  - Email
  - Phone number
  - Password

### Product Sort and Filter
- Users can sort products by:
  - Price
  - Popularity
  - Rating
- Filtering options include:
  - Categories
  - Price ranges
  - Ratings

### Cart Functionality
- Users can add or remove products from their cart.
- Displays a list of added products, their quantities, and the total price.
- Includes a checkout button that navigates to a checkout page.

## Admin Panel (Optional)
- Admin users can:
  - Add new products to the inventory.
  - Delete existing products.
  - View order details.

**Demo Admin Credentials:**
- Email: admin@mail.com
- Password: testpass1234

> Note: Admin credentials are hardcoded for demonstration purposes. For real-world applications, ensure a secure and dynamic authentication mechanism.

## Getting Started

### Prerequisites
- Install [Flutter](https://flutter.dev/docs/get-started/install) and set up your development environment.

### Installation Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd ecommerce-flutter-app
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app on an emulator or connected device:
   ```bash
   flutter run
   ```

## Development Notes
- The project uses **Firebase** for user authentication and database management.
- Infinite scrolling is implemented using pagination.
- Ensure you have a valid Firebase project set up and configured in the app.

