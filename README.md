

# Django Ecommerce Project

Django Commerce is an open-source e-commerce project built using Django, a high-level Python web framework. It provides a robust foundation for creating online stores with features such as product management, shopping cart functionality, user authentication, order processing, and payment integration with Stripe.


## Features
- Product Catalog: Browse and search for products based on categories and keywords.
- Shopping Cart: Manage your shopping cart with the ability to add, remove, and edit items.
- User Authentication: Create user accounts, log in, and manage your personal information.
- Order Processing: Place orders, view order history, and track order status.
- Payment Integration: Securely process payments using Stripe, a popular payment gateway.


## Set up your Stripe API keys:
- Sign up for a free Stripe account at https://stripe.com.
- Obtain your Stripe API keys (publishable and secret keys).
- Update the .env file with your Stripe API keys.


## Getting started

Steps:

1. Clone the repository: `git clone https://github.com/your-username/django-commerce.git`
2. Navigate to the project directory: `cd django-commerce`
3. Create and activate a virtual environment: `python3 -m venv venv` `source venv/bin/activate`
4. Install the project dependencies: `pip install -r requirements.txt`
7. Create your Database and add it's details in .evn file.
8. Apply the database migrations: `python manage.py migrate`
9. Start the development server: `python manage.py runserver`
10. Open your web browser and visit: http://localhost:8000 to access the application.



## Contributing
Contributions are welcome! If you'd like to contribute to Django Commerce, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

Please ensure that your code follows the project's coding conventions and includes appropriate tests and documentation.


## License
This project is licensed under the MIT License.


## Acknowledgements
Special thanks to Stripe for providing secure and reliable payment integration services.
