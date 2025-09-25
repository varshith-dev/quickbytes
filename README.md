QuickBytes - Canteen Ordering & Management System
<p align="center">
<img src="https://www.google.com/search?q=https://raw.githubusercontent.com/user/repo/main/screenshots/logo.png" alt="QuickBytes Logo" width="150">
</p>

<p align="center">
A modern, feature-rich, and real-time Point of Sale (POS) system designed for canteens, food trucks, and small cafes. Built with HTML, Tailwind CSS, and Firebase, QuickBytes provides a seamless experience for managing sales, inventory, and reporting.
</p>

<p align="center">
<img alt="GitHub language count" src="https://www.google.com/search?q=https://img.shields.io/github/languages/count/your-username/your-repo-name%3Fstyle%3Dfor-the-badge%26color%3Dblue">
<img alt="GitHub top language" src="https://www.google.com/search?q=https://img.shields.io/github/languages/top/your-username/your-repo-name%3Fstyle%3Dfor-the-badge%26color%3Dyellow">
<img alt="License" src="https://www.google.com/search?q=https://img.shields.io/github/license/your-username/your-repo-name%3Fstyle%3Dfor-the-badge%26color%3Dgreen">
</p>

Live Demo
(Note: The live demo link is for demonstration purposes. For full functionality, including data persistence, please follow the setup instructions below.)

✨ Key Features
QuickBytes is packed with unique and powerful features that set it apart from other platforms:

Real-time Dashboard: Get an at-a-glance overview of today's revenue, total orders, and items that are running low on stock.

Interactive POS Menu: A clean, responsive grid layout for your menu items with powerful live search, category filtering, and sorting (by name or price).

Dynamic Cart System:

Manually adjust item quantities.

Easily remove items from the cart.

Apply optional discounts (fixed amount or percentage) at checkout.

Professional Bill Generation: Instantly generate and preview professional, thermal-printer-friendly PDF bills using jsPDF.

Comprehensive Bill History: View, download (as PDF or Excel), and manage all past orders.

Sales & Analytics: A dedicated reporting view with charts showing top-selling items. Filter sales data by period (Today, This Week, All Time).

Full Menu Management: A simple interface to perform CRUD (Create, Read, Update, Delete) operations on menu items.

Dynamic Category Management: Add or delete item categories on the fly from a dedicated management panel.

Advanced Stock Management:

Unique "Quick Add" Feature: Instantly add +5, +10, or +25 to your stock with a single click.

Visual low-stock and out-of-stock indicators.

Data Export: Download your entire menu and stock list as an .xlsx (Excel) file for offline analysis or record-keeping.

Customizable Settings: Easily configure the store name, tax rate, and a custom receipt footer message.

Modern UI/UX: A beautiful, fully responsive interface with seamless Dark and Light mode support.

📸 Screenshots
https://drive.google.com/drive/folders/1I5Htlr8l12MQHfo3Fz8XVlgjWy0bSOhm?usp=sharing
Dashboard & POS Menu

Cart & Checkout





Stock & Menu Management

Sales Reports & Bill History





Settings & Dark Mode



💻 Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ES6 Modules)

Backend & Database: Google Firebase (Firestore Realtime Database)


🚀 Setup and Installation
To get this project running locally, follow these simple steps:

Clone the repository:

git clone https://github.com/varshith-dev/quickbytes/
cd quickbytes

Set up Firebase:

Go to the Firebase Console and create a new project.

In your project, go to Build > Firestore Database and create a new database. Start in test mode for easy setup (you can configure security rules later).

Go to your Project Settings (click the ⚙️ icon) and scroll down to the "Your apps" section.

Click on the Web icon (</>) to create a new web app.

After registering the app, Firebase will provide you with a firebaseConfig object. Copy this object.

Configure the Project:

Open the index.html file.

Find the firebaseConfig object within the <script type="module"> tag (around line 300).

Replace the placeholder keys with the actual keys you copied from your Firebase project.



Create Firestore Collections:
For the app to work, you need to manually create the following collections in your Firestore Database:

categories: Stores the menu categories. Each document should have a name field (e.g., { name: "Beverages" }).

menu: Stores the menu items.

orders: Stores completed orders.

Run the Application:
Simply open the index.html file in your web browser. You can use a live server extension in your code editor for the best experience.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

Made with ❤️ by [Your Name]
