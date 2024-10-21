# Clothes Ecommerce Platform

## Overview
    
This is a complete Ecommerce platform dedicated to clothing, built using .NET Web API for the backend and Angular for the frontend. The platform allows users to browse, search, and purchase clothes while providing a robust admin panel for managing products, orders, and users.


## Sequence diagram
This sequence diagram illustrates the basic request and response flow in an e-commerce system for a product page request. Here's a breakdown of the steps:

![image](https://github.com/user-attachments/assets/8599a24f-4a8f-48bd-9de9-6f75d2448438)

1. User Action:

   - The user requests a product page, typically by clicking a link or entering a URL.


2. Client Request:

   - The client (browser or app) sends an HTTP GET request to the web server for a specific product (e.g., /product/{id}).


3. Web Server Processing:

   - The web server receives the request and forwards it to the application server.


4. Application Server Processing:

   - The application server processes the request and queries the database for the product details.


5. Database Interaction:

   - The database retrieves the requested product data and returns it to the application server.


6. Data Processing:

     - The application server processes the data (e.g., formatting, adding additional information).


7. Response Generation:

     - The processed data is sent back to the web server.
     - The web server generates an HTML response.


8. Client Reception:

    - The client receives the HTML response.


9. User Interface:

   - The client renders the HTML and displays the product page to the user.

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


