# Ecommerce


This is a fully functional, secure e-commerce web application built using HTML, CSS, JavaScript, Python, Django, and SQL. The project includes user authentication, email verification, and complete shopping functionality, from product browsing to payment processing.

## Project Structure

The project is organized into four main folders and six HTML files:

### Folders:
- **ecommerce/**: main Project.
- **ecommerceapp/**: ecommerce app 
- **authcart/**: authcart app
- **media/**: to keep media files here
- **static/**: to keep static files here
- **templates/**: Visible content here

### Files:
- **idb.sqlite3**: database file.
- **manage.py**: command-line utility that lets you interact with your Django project.

## Technology Stack

- **Frontend**: 
  - HTML, CSS, JavaScript
- **Backend**: 
  - Python, Django
- **Database**: 
  - SQLite
- **Authentication**: 
  - Django's built-in authentication system with email verification
- **Payment Integration**: 
  - (Paytm payment gateway used)

## Features

- **Responsive Design**: The website is fully responsive, ensuring it looks great on devices of all sizes.
- **User Registration & Authentication**: Users can sign up with their email, verify their account via email authentication, and log in securely.
- **Product Browsing**: Users can explore a wide variety of products available for purchase.
- **Add to Cart**: Users can add products to their cart for future checkout.
- **Checkout Process**: A streamlined checkout process allows users to review their cart, update quantities, and proceed to payment.
- **Payment Gateway**: Integrated payment system for secure transactions.
- **Order History**: Users can view their order history after successful purchases.
- **Logout**: Users can securely log out of their accounts when they are done.
- **Contact Form**: A simple and effective contact form to allow visitors to reach out to me easily.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SArun07/Ecommerce.git/
    ```

2. Navigate to the project folder:
    ```bash
    cd Ecommerce
    ```

3. Write here you email_host user and password in ecommerce/setting.py:
    ```bash
    EMAIL_HOST_USER='write your email@gmail.com'
    EMAIL_HOST_PASSWORD='enter password'
    ```

3. Run the command in terminal:
    ```bash
    Python manage.py runserver
    ```




## Future Enhancements

- **Blog CMS**: Implement a content management system (CMS) to allow easy updates to the blog section.
- **SEO Improvements**: Optimize the website for search engines to improve visibility.
- **Dynamic Features**: Add more interactivity and dynamic features using JavaScript and AJAX.

## Contact

Feel free to reach out via the contact form on the website or directly through my [LinkedIn](https://www.linkedin.com/in/arunsingh027).

---

## Project Structure

```plaintext
ecommerce/
│
├── ecommerceapp/               # Main ecommerce functionality
├── authcart/                   # Authentication and cart management
├── media/                      # Uploaded media files
├── static/                     # Static files (CSS, JavaScript, images)
├── templates/                  # HTML templates
├── db.sqlite3                  # SQLite database file
├── manage.py                   # Django management script
├── README.md                   # Project documentation
└── 
plaintext```


Thank you for visiting Ecommerce! Stay tuned for more content and projects.

