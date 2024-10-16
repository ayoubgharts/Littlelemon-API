# Little Lemon API

# Author
> Ayoub Ghiouani.

## Overview
The Little Lemon API is a back-end service for the Little Lemon restaurant, allowing users to manage menu items, orders, and user roles. This API is built using Django, Django REST Framework (DRF), and Djoser for token-based authentication. It supports various functionalities for different user roles, including admins, managers, delivery crew, and customers.

## Features
- **Admin Features:**
  - Assign users to the manager group.
  - Add menu items and categories.
  
- **Manager Features:**
  - Log in and manage menu items.
  - Update the item of the day.
  - Assign users to the delivery crew and orders to them.
  
- **Delivery Crew Features:**
  - Access and update assigned orders.
  
- **Customer Features:**
  - Register and log in to access the API.
  - Browse categories and menu items.
  - Paginate and sort menu items by price.
  - Add items to the cart and place orders.
  - View previous orders.

## Getting Started

### Prerequisites
- Python 3.x
- Pipenv

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd LittleLemon
