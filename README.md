# TastyBite - Restaurant Food Ordering Website

Welcome to TastyBite! This is a comprehensive food ordering website developed using C#. This README file will guide you through the structure, setup, and usage of the TastyBite project.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Registration and Authentication**: Users can register, log in, and manage their profiles.
- **Menu Browsing**: Users can browse the restaurant's menu categorized by different food types.
- **Order Management**: Users can place orders, view order history, and track current orders.
- **Admin Dashboard**: Admins can manage menu items, view all orders, and handle user management.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: C#, ASP.NET Core
- **Database**: SQL Server
- **Authentication**: ASP.NET Identity

## Installation

### Prerequisites

- .NET SDK 5.0 or higher
- SQL Server
- Visual Studio 2019 or higher

### Steps

1. **Clone the repository**
    ```sh
    git clone https://github.com/iamanrajput/TastyBite.git
    ```

2. **Navigate to the project directory**
    ```sh
    cd TastyBite
    ```

3. **Set up the database**
    - Update the connection string in `appsettings.json` to point to your SQL Server instance.
    - Apply migrations to create the database schema.
    ```sh
    dotnet ef database update
    ```

4. **Run the application**
    ```sh
    dotnet run
    ```

5. **Open in browser**
    Open your browser and navigate to `https://localhost:5001`

## Usage

### User Flow

1. **Register/Login**: Users can create an account or log in using existing credentials.
2. **Browse Menu**: Users can browse through different categories of food items.
3. **Place Order**: Users can add items to the cart and place an order.
4. **Order Tracking**: Users can track the status of their current orders and view past orders.
5. **Admin Access**: Admins can log in to access the dashboard to manage the menu and orders.

### Admin Flow

1. **Login as Admin**: Use admin credentials to log in.
2. **Manage Menu**: Add, edit, or delete menu items.
3. **View Orders**: See all user orders and their statuses.
4. **User Management**: Manage user accounts.

## Project Structure
TastyBite
<para>
│ README.md
│ TastyBite.sln
│
└───TastyBite
│ appsettings.json
│ Program.cs
│ Startup.cs
│
├───Controllers
│ AccountController.cs
│ AdminController.cs
│ HomeController.cs
│ OrderController.cs
│
├───Models
│ ApplicationUser.cs
│ FoodItem.cs
│ Order.cs
│
├───Views
│ ├───Account
│ ├───Admin
│ ├───Home
│ ├───Order
│ └───Shared
│
├───wwwroot
│ ├───css
│ ├───js
│ └───images
│
├───Data
├───Migrations
└───Services
<para>
## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Contact

For any inquiries or issues, please contact:

- **Name**: Aman Raj
- **Email**: theamanrajput15@gmail.com
- **GitHub**: [iamanrajput](https://github.com/iamanrajput)

---

Thank you for using TastyBite! Enjoy your meal!

