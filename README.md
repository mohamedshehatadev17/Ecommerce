# Clothes Ecommerce Platform

## Overview

This is a complete Ecommerce platform dedicated to clothing, built using .NET Web API for the backend and Angular for the frontend. The platform allows users to browse, search, and purchase clothes while providing a robust admin panel for managing products, orders, and users.

## Features

- **User Authentication:** Secure login and registration system.
- **Product Management:** Add, edit, and remove clothing items with categories and filters.
- **Product Filtering:** Search and filter products by categories, price, size, and color.
- **Pagination:** Efficient product browsing with paginated results for better user experience.
- **Shopping Cart:** Real-time cart management with the ability to add, update, and remove items.
- **Order Management:** Process and manage customer orders.
- **Responsive Design:** Optimized for all devices using Bootstrap.
- **Admin Dashboard:** Manage clothing products, orders, and user information.
- **Payment Integration:** Secure payment handling for clothing purchases.

## Technologies Used

### Backend
- **.NET Web API** for building RESTful services
- **Entity Framework Core** for database operations
- **SQL Server** for data storage
- **C#** for backend logic

### Frontend
- **Angular** for building a dynamic single-page application
- **Bootstrap** for a responsive, mobile-first design
- **HTML5/CSS3** for structure and styling

### Other Tools
- **JWT Authentication** for securing API endpoints
- **Swagger** for API documentation and testing
- **RESTful API** for client-server communication

## Getting Started

### Prerequisites

- .NET SDK
- Node.js and Angular CLI
- SQL Server

### Setup

1. Clone the repository:
     ```bash
     git clone https://github.com/mohamedshehatadev17/Ecommerce.git
2.Navigate to the backend project and restore dependencies:
     ```bash
     
       cd Ecommerce/Backend
       dotnet restore
3.Apply migrations to set up the database:
  ```bash
       dotnet ef database update
```
4.Start the backend server:
   dotnet run
5-Navigate to the frontend project, install dependencies, and serve the Angular app:

      cd ../Frontend
      npm install
      ng serve
6.Open the browser and navigate to http://localhost:4200 to access the frontend: 
frontend Repo : 
```bash
     https://github.com/mohamedshehatadev17/Ecommerce_Front
```
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or fixes.


