# E-Commerce Website

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)

## Installation

To set up the e-commerce website, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/izzatkarimov/e-commerce.git
   ```

2. Navigate to the project directory:
   ```bash
   cd e-commerce
   ```

3. Create a virtual environment:
   ```bash
   python -m venv env
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     .\env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```

5. Run database migrations:
   ```bash
   python manage.py migrate
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

Once the server is running, you can access the website at `http://127.0.0.1:8000/`. You can browse products, add them to your cart, and proceed to checkout.

## Screenshots

### Home Page:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/38f04552-7736-4ceb-a708-308d8b0bb88e)

### Cart Page:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/b65615c0-9490-40bf-94ec-455dde196d6b)

### Checkout Page:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/c01c8b28-c80d-4564-b697-7c5bd2ff3d84)

### Checkout Page with Payment:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/cec1c8ac-f961-4da4-9f3a-b888ea2b274f)

### Paypal Integration:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/99cc8cb6-6981-4316-9d2e-0e772a97c298)

### Successful Payment:
![Website Screenshot](https://github.com/izzatkarimov/e-commerce/assets/108251704/034a9020-6da6-4db4-ae22-51c9f42ac05c)
