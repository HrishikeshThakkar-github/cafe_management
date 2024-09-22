# Coffee Shop Ordering Application

## Introduction
The **Coffee Shop Ordering Application** is designed to streamline the ordering process for both customers and staff. It offers seamless order placement and tracking, ensuring efficient operations in a coffee shop setting. The system is structured to accommodate three distinct user roles, each with unique privileges:

- **Admin**
- **Employee**
- **User**

## Features

### Unregistered Users
Unregistered users can:
- Register an account.
- Browse the coffee shop menu.
- Select meal types.
- Add items to the cart.
- Confirm orders with address and phone number.

### Registered Users (USER)
Registered users have additional benefits, including:
- Updating personal information.
- Ordering food with a **10% discount**.
- Viewing active orders (statuses: **ORDERED** and **IN PREPARATION**).
- Accessing order history (statuses: **IN DELIVERY**).

### Employees (EMPLOYEE)
Employees have access to:
- Reviewing incoming orders.
- Updating order statuses (**IN PREPARATION** or **IN DELIVERY**).
- Accessing order history.

### Administrators (ADMIN)
Administrators have full control over the system, with the ability to:
- Manage meal types (create, update, delete).
- Manage meals (create, update, delete).
- Manage users (logically delete users).
- View active orders.
- Delete orders and associated items.
- Access order history.
- Manage employee data.

## Application UI Preview
The application features a responsive design that enhances user experience. Key aspects of the UI include:

- Users can select a category to view available offers.
- Items can be added to the cart with specified quantities.
- Order confirmation requires the input of an address and phone number.
- Input validation is implemented to ensure a valid phone number.
- Registered users automatically receive a **10% discount**.
- Logged-in users' details are pre-populated during order placement.
- User profiles support profile and password management, with old password verification required for password changes.
- Alerts are provided if a username or email already exists during registration.

## Additional Information
- Employees manage the status of orders, while administrators have full control over order and user management.
- Once delivered, orders are moved to the **order history**.
- The **Login component** is displayed when the application starts.

## How to Run the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/coffee-shop-ordering-app.git
