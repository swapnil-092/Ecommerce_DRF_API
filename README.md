# E-Commerce API with Django Rest Framework

## Problem Description

Create a comprehensive e-commerce website using Django Rest Framework that allows users to browse products, add them to their cart, place orders, and manage their accounts. Key features include product listings, category organization, user authentication, and support for GET and POST methods.

## Tech Stack

- **Python**: Utilize Python as the primary programming language.
- **Django**: Use Django as the web framework for backend development.
- **Django Rest Framework**: Employ DRF for building RESTful APIs.
- **SQLite**: Use SQLite as the database system for storing product, category, order, and user data.

## Libraries and Dependencies

- **Django**: A high-level Python web framework.
- **Django Rest Framework (DRF)**: A powerful and flexible toolkit for building Web APIs.
- **DRF Token Authentication**: For securing API endpoints and user authentication.
- **SQLite**: A lightweight, serverless database engine.
- **Python Requests**: For testing and interacting with API endpoints.
- **Postman (Optional)**: For API testing and validation.

## Features

- **User Authentication**: Implement user registration and login with token-based authentication.
- **Product Listings**: Display products with details such as name, description, price, and category.
- **Categories**: Organize products into categories for easy navigation.
- **Cart Management**: Allow users to add products to their cart and manage cart items.
- **Order Placement**: Enable users to place orders for items in their cart.
- **User Account**: Allow users to update their profile and view order history.

## Setup and Usage

Follow these steps to set up and run the project on your local machine:

### Prerequisites

- Python and Django should be installed on your system.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/ecommerce-website.git
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use venv\Scripts\activate
    ```

3. Install the required packages using pip:

    ```bash
    pip install -r requirements.txt
    ```

4. Run database migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Create a superuser for admin access:

    ```bash
    python manage.py createsuperuser
    ```

6. Start the development server:

    ```bash
    python manage.py runserver
    ```

7. Access the admin panel at [http://localhost:8000/admin/](http://localhost:8000/admin/) and log in with the superuser credentials.

## Usage

Use the following API endpoints for various functionalities:

- **Product Listings**: `/api/products/`
- **Categories**: `/api/categories/`
- **Cart Management**: `/api/cart/`
- **Order Placement**: `/api/orders/`
- **User Authentication**: `/api/token/`

## Testing

You can use tools like Python Requests or Postman to test the API endpoints. For detailed API usage, refer to the provided documentation.

## Results and Conclusion

This project showcases the development of a fully functional e-commerce website using Django Rest Framework. It offers essential features for managing products, user authentication, cart operations, and order placement. By following the setup instructions and exploring the provided API endpoints, you can customize and expand this e-commerce platform to suit specific business requirements.

