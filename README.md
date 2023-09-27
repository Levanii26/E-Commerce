# E-Commerce Project README

# Table of Contents
- Introduction
- Features
- Technologies Used
- Installation
- Usage
- Project Structure
- Contributing

# Introduction
- This E-Commerce project is built using Django, JavaScript, and integrates various features including Login Authentication, Product Category-wise listing, Add to Cart, Wishlist, Razorpay Payment Gateway for secure online payments, and the ability to add and manage delivery addresses.

# Features
1.User Authentication:

- Users can create accounts, log in, and log out securely.
- Password reset functionality is available in case of forgotten passwords.
- Product Category-wise Listing:

- Products are categorized for easy navigation.
- Users can browse products by category.

2.Add to Cart:

- Users can add products to their shopping cart.
- Quantity and product details can be adjusted in the cart.

3.Wishlist:

- Users can add products to their wishlist for future reference.
- Wishlist items can be moved to the cart.

4.Razorpay Payment Gateway:

- Secure and reliable payment processing using Razorpay.
- Users can make online payments for their orders.

5.Add Addresses:

- Users can add and manage multiple delivery addresses.
- During checkout, they can choose from their saved addresses.
Technologies Used
- Django: A Python web framework used for building the backend of the application.
- JavaScript: Used for dynamic frontend features.
- HTML/CSS: For structuring and styling the user interface.
- Razorpay Payment Gateway: For processing online payments.

# Installation
1.Clone the repository:

shell

- Copy code
 - git clone https://github.com/Levanii26/e-commerce-project.git
- cd e-commerce-project
2.Create a virtual environment (recommended):

shell

 - Copy code
 - python -m venv venv
- Activate the virtual environment:

3.On Windows:
shell

- Copy code
- venv\Scripts\activate
- On macOS and Linux:

shell

- Copy code
- source venv/bin/activate
4.Install dependencies:

shell

- Copy code
- pip install -r requirements.txt

5.Migrate the database:

shell

- Copy code
- python manage.py migrate
6.Create a superuser account:

shell

- Copy code
- python manage.py createsuperuser
7.Start the development server:

shell
- Copy code
- python manage.py runserver
- Open a web browser and navigate to http://localhost:8000 to access the application.

# Usage
- Visit the website and create an account or log in.
- Browse products by category.
- Add products to your cart.
- View and edit your cart.
- Move items to the wishlist.
- Proceed to checkout and make payments securely using Razorpay.
- Manage your delivery addresses in your profile.

# Contributing
- If you'd like to contribute to this project, please follow these steps:

1.Fork the repository.

2.Create a new branch for your feature or bug fix.

3.Make your changes and test them thoroughly.

4.Submit a pull request with a clear description of your changes.# E-Commerce
