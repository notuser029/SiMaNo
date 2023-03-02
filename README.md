# SiMaNo

SiMaNo is a web application designed to handle restaurant orders. This repository contains the source code for the application, written in Python.

## Getting Started

To run SiMaNo on your local machine, you'll need to have Python 3 installed. You can download it from the [official Python website](https://www.python.org/downloads/).

You'll also need to install several Python packages. You can install them using pip, the Python package manager. Here's a list of the packages you'll need:

- Flask
- SQLAlchemy
- WTForms

To install the packages, open a terminal or command prompt and run the following command:

```
pip install flask sqlalchemy wtforms
```

Once you have Python and the required packages installed, you can run SiMaNo by running the following command in the project directory:

```
python run.py
```

This will start the Flask development server and you can access the application by visiting http://localhost:5000 in your web browser.

## Features

SiMaNo has the following features:

- A user can create an account and log in to the application.
- A user can place an order by selecting items from a menu.
- A user can view their order history and track the status of their current order.
- A restaurant owner can log in to the application and view all orders placed.
- A restaurant owner can update the status of an order, such as marking it as completed.

## Contributing

If you'd like to contribute to SiMaNo, please open an issue or submit a pull request. We welcome all contributions!

## License

SiMaNo is licensed under the MIT License.
