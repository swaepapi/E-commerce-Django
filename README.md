# E-commerce Website with Django

## Overview

This project is a full-fledged e-commerce platform developed using Django. It provides features for users to browse products, manage shopping carts, and complete purchases. Admins can manage the product inventory, view orders, and monitor customer activities through the admin interface.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
  - [Clone the Repository](#clone-the-repository)
  - [Create a Virtual Environment](#create-a-virtual-environment)
  - [Install Dependencies](#install-dependencies)
  - [Configure the Database](#configure-the-database)
  - [Run Migrations](#run-migrations)
  - [Create a Superuser](#create-a-superuser)
  - [Run the Development Server](#run-the-development-server)
- [Usage](#usage)
  - [Admin Dashboard](#admin-dashboard)
  - [User Workflow](#user-workflow)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- User Registration and Authentication (Login, Logout)
- Product Catalog with Categories and Filtering
- Shopping Cart Management
- Order Checkout with Payment Gateway Integration
- Order Management and Invoice Generation
- Admin Dashboard for Product, Category, and Order Management
- Product Reviews and Ratings
- Responsive Design for Mobile and Desktop

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (Bootstrap for UI)
- **Database**: SQLite (development), PostgreSQL or MySQL (production)
- **Payment Gateway**: Stripe or PayPal (configurable)
- **Others**: Django REST Framework, Celery for asynchronous tasks, Redis as message broker

## Setup and Installation

### Prerequisites

- Python 3.8 or above
- Django 4.x
- Git
- PostgreSQL or MySQL (for production)
- Stripe or PayPal credentials (for payment integration)

### Clone the Repository

```bash
git clone https://github.com/swaepapi/E-commerce-Django.git
cd ecommerce-website
