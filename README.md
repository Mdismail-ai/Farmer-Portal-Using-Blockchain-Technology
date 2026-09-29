A Study of Blockchain Technology in Farmer's Portal
📌 Project Overview

A Study of Blockchain Technology in Farmer's Portal is a web-based agricultural platform developed using Python and Django. The project provides a portal where farmers can manage agricultural products and customers can browse and order products.

The project also demonstrates the use of blockchain technology to maintain transaction-related information in a secure and structured manner.

🎯 Objectives

Provide an online portal for farmers and customers.

Allow farmers to add and manage agricultural products.

Allow users to browse available products.

Provide product search functionality.

Allow customers to place orders.

Manage product quantities and orders.

Demonstrate blockchain concepts in an agricultural application.

Store application data using a database.

🛠️ Technologies Used
Frontend

HTML

CSS

JavaScript

Backend

Python 3.6.8

Django 2.0

Machine Learning / Data Processing

TensorFlow 1.14.0

Keras 2.3.1

NumPy

Pandas

Scikit-learn

OpenCV

Database

SQLite

MySQL support through PyMySQL/mysqlclient

Blockchain

Python-based blockchain implementation

Blockchain transaction/record concepts

Smart contract reference

📂 Project Structure
A-STUDY-OF-BLOCKCHAIN-TECHNOLOGY-IN-FARMER-S-PORTAL--main/
│
├── FarmerPortal/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── FarmerPortalApp/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── images/
├── Block.py
├── Blockchain.py
├── blockchain_contract.txt
├── db.sqlite3
├── manage.py
├── requriments.txt
├── run.bat
└── README.md

⚙️ Installation
1. Install Python

This project uses an older Python/Django environment.

Recommended Python version:

Python 3.6.8


Check your Python version:

python --version

2. Clone the Repository
git clone <YOUR-GITHUB-REPOSITORY-URL>


Move into the project directory:

cd A-STUDY-OF-BLOCKCHAIN-TECHNOLOGY-IN-FARMER-S-PORTAL--main

3. Install Dependencies

The dependency file in this project is named:

requriments.txt


Install the packages using:

python -m pip install -r requriments.txt

▶️ Running the Project

Start the Django development server:

python manage.py runserver


The server will start at:

http://127.0.0.1:8000/


The project currently provides the following main pages:

http://127.0.0.1:8000/index.html
http://127.0.0.1:8000/Login.html
http://127.0.0.1:8000/Register.html
http://127.0.0.1:8000/AddProduct.html
http://127.0.0.1:8000/BrowseProducts.html
http://127.0.0.1:8000/ViewOrders.html


Django administration:

http://127.0.0.1:8000/admin/

👨‍🌾 Main Features
Farmer / Supplier

User registration

User login

Add agricultural products

Update product quantity

View orders

Manage product information

Customer / Consumer

User registration

Login

Browse products

Search products

Book/order products

View order information

Blockchain

The project contains Python implementations related to blockchain functionality:

Block.py
Blockchain.py
blockchain_contract.txt


These components demonstrate how blockchain concepts can be incorporated into a farmer-oriented portal.

🗄️ Database

The project includes an SQLite database:

db.sqlite3


Django models and database operations are handled through:

FarmerPortalApp/models.py

🔐 Security Note

This project is primarily intended for academic and educational purposes. Before using it in a production environment, authentication, database credentials, secret keys, input validation, blockchain implementation, and other security configurations should be reviewed and strengthened.

📚 Project Type

Academic / Educational Project

This project demonstrates the application of blockchain technology in an agricultural/farmer portal using Django and Python.

👤 Author

Mdismail-ai

GitHub:
https://github.com/Mdismail-ai

📄 License

This project is intended for educational and academic purposes.
