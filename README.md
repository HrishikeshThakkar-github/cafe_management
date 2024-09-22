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


![image](https://github.com/user-attachments/assets/bce5abf8-4d2e-4f0f-9941-fb0d28aa8bd7)
![image](https://github.com/user-attachments/assets/5f66831f-81bf-4143-bf96-e964b78d6218)
![image](https://github.com/user-attachments/assets/c81e9314-652e-4ca9-b840-534d5662796d)
## Admin panel
![image](https://github.com/user-attachments/assets/98c244bc-6079-4a0c-9da8-32a679e4e258)
![image](https://github.com/user-attachments/assets/cf75ae21-5b55-44b1-af07-eef49443506e)
![image](https://github.com/user-attachments/assets/617e85c8-07e7-4fd0-b023-533d58dd8848)
![image](https://github.com/user-attachments/assets/1c58a0cf-4087-40e2-ae10-696855c70c7b)
![image](https://github.com/user-attachments/assets/f9df0e2f-9b9e-478e-b777-f2ae3b6ae25b)
![image](https://github.com/user-attachments/assets/4c043934-f312-44b2-ab48-612c1b46d5fa)
## user panel
![image](https://github.com/user-attachments/assets/7db41786-9d74-4e98-b1a4-d5f77b5114df)
## Employee panel
![image](https://github.com/user-attachments/assets/a02f9605-e416-4871-97f8-390a4c4b640a)
![image](https://github.com/user-attachments/assets/26fc86b1-20b0-44e6-90f0-4b0461a14ea3)


