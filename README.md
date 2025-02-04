# MaxCinema
🎬 Movie Shop - ASP.NET Core MVC

## Overview📌

Movie Shop is a web application built using ASP.NET Core MVC and Entity Framework (Code First) and MSSQL database. It allows users to browse, add, and purchase movies, while also providing an admin dashboard for order management.

## Features🚀

### Movie Management🎥

Add new movies with details like Title, Director, Release Year, Price.

Optional image URL for movie posters.

Display all movies using partial views.

Search and filter movies by title, director, or release year.

### Shopping Cart🛒

Users can add movies to the cart.

Supports multiple copies of the same movie.

Allows removing movies from the cart.

Checkout with user registration or guest checkout.

### Order Management📦

View all orders for a specific customer.

Admin dashboard to see all orders from newest to oldest.

Orders display total cost and movie details.

### Front Page (Dynamic Content)🏆

Top 5 most popular movies based on orders.

Newest and oldest 5 movies.

5 cheapest movies.

Display the customer who placed the most expensive order or spent the most overall.

### Additional Features (Optional Enhancements)🔎

Pagination for movies list.

Search functionality using query strings.

Delivery vs. Billing Address Autofill.

Actor Management: Associate actors with movies and display them.

## Technologies Used🏗️

ASP.NET Core MVC

Entity Framework Core (Code First)

SQL Server

Sessions & Cookies for Shopping Cart

LINQ for Data Queries

## Project Structure📂

MovieShop/
│-- Controllers/        # Handles requests and business logic
│-- Models/            # Database entities
│-- Views/             # Razor views (HTML + C#)
│-- Data/              # Entity Framework context
│-- wwwroot/           # Static assets (CSS, JS, images)
│-- appsettings.json   # Configuration file

## Setup Instructions🛠️

1️⃣ Clone Repository

git clone https://github.com/your-username/MovieShop.git
cd MovieShop

2️⃣ Configure Database

Open appsettings.json and update the SQL Server connection string.

3️⃣ Apply Migrations

dotnet ef migrations add InitialCreate
dotnet ef database update

4️⃣ Run the Application

dotnet run

Open http://localhost:5000/ in your browser.

## Future Enhancements🎯

Implement user authentication for admin and customers.

Integrate payment gateway for real purchases.

Add movie reviews and ratings.
