# Laravel Blog CMS 🚀

A full-featured, professional Blog and Content Management System (CMS) built with the Laravel framework. This application provides a robust backend for content creators to manage their articles, categories, and user authentication seamlessly.

## 🌟 Features

* **User Authentication & Authorization**: Secure login, registration, and session management.
* **Admin Dashboard**: An intuitive and restricted control panel for managing content.
* **Post Management (CRUD)**: Create, Read, Update, and Delete blog posts with ease.
* **Category System**: Organize posts dynamically by categories for better content discoverability.
* **Clean & Responsive UI**: User-friendly interface for both the public-facing blog and the admin dashboard.
* **MVC Architecture**: Strictly follows Laravel's Model-View-Controller design pattern for maintainable, readable, and scalable code.

## 🛠️ Tech Stack

* **Backend**: PHP, Laravel
* **Frontend**: HTML5, CSS3, JavaScript, Blade Templating
* **Database**: MySQL
* **Tools & Utilities**: Composer, Git, NPM, Trix Editor

## ⚙️ Installation & Setup

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your local machine:
* PHP >= 8.0
* Composer
* Node.js & NPM
* MySQL or any compatible relational database

### Step-by-Step Guide

1. **Clone the repository**
    ```bash
       git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
       cd your-repo-name

2. Install PHP dependencies
    ```bash
       composer install

3. Install frontend dependencies and compile assets
    ```bash
       npm install
       npm run dev
4. Environment Setup
Copy the example environment file to create your own .env file.
    ```bash
       cp .env.example .env

5. Run the Application
    ```bash
       php artisan serve
