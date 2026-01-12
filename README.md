# Angular E-Commerce Project

## Project Overview

This is a **B2B E-Commerce Web Application** built with Angular. It simulates a commerce portal where multiple types of users interact:  

1. **Admin** – Manages products, users, and platform operations.  
2. **Seller** – Lists and manages products for sale.  
3. **Buyer/End User** – Purchases products, manages cart, and tracks orders.  

The application is inspired by platforms like **Amazon, Flipkart, Snapdeal**, and provides a learning experience for understanding **B2B e-commerce workflows**. While not all features of these platforms are implemented, it covers the core functionality and user role management.

---

## Features by User Role

### Admin
- **Login URL:** `http://localhost:4200/#/admin-login`  
- **Credentials:**  
  - Email: `admin@gmail.com`  
  - Password: `123456`  
- **Capabilities:**  
  - Manage Products: view, add, edit, delete  
  - Manage Users (Seller, Buyer, Admin): view, add, edit, delete  
  - Manage Own Profile: edit/update profile  

### Seller
- **Login URL:** `http://localhost:4200/#/sign-in`  
- **Credentials:**  
  - Email: `seller@gmail.com`  
  - Password: `123456`  
- **Capabilities:**  
  - Manage Orders (WIP)  
  - Manage Products: view, add, edit, delete  
  - Manage Own Profile: edit/update profile  

### Buyer / End User
- **Login URL:** `http://localhost:4200/#/sign-in`  
- **Credentials:**  
  - Email: `buyer@gmail.com`  
  - Password: `123456`  
- **Capabilities:**  
  - Browse and buy products  
  - Add products to cart  
  - View product details  
  - Change delivery address  
  - Track orders  
  - Manage Own Profile: edit/update profile  

> **Note:** If credentials don’t work, check the mock API at `http://localhost:3000/`.

---

## Project Setup Instructions

1. **Clone the project:**  
   ```bash
   git clone https://github.com/AntimaTyagi/angular-ecommerce-sp1.git
   ```

2. **Navigate into the project folder:**  
   ```bash
   cd angular-ecommerce
   ```

3. **Pull the latest develop branch:**  
   ```bash
   git pull origin develop
   ```

4. **Install Node.js:**  
   Download from [https://nodejs.org/en/](https://nodejs.org/en/)  

5. **Install project dependencies:**  
   ```bash
   npm install
   ```

6. **Install JSON Server (mock API):**  
   ```bash
   npm install -g json-server
   ```

7. **Install Angular CLI:**  
   ```bash
   npm install -g @angular/cli
   ```

8. **Open two terminal windows/command prompts:**  

   **Terminal 1:** Run the Angular app  
   ```bash
   ng serve
   ```  

   **Terminal 2:** Run the JSON mock API  
   ```bash
   json-server --watch mock-api-data.json
   ```

> **Note:** If you face errors during installation, clear npm cache:  
> ```bash
> npm cache clean --force
> ```

9. **Access the application:**  
   - Angular app: `http://localhost:4200`  
   - Mock API: `http://localhost:3000/`  

For more information about JSON Server, check [https://www.npmjs.com/package/json-server](https://www.npmjs.com/package/json-server).

---

## Technical Knowledge Gained

- Understanding of **B2B e-commerce applications**  
- Using **JSON Server** to simulate backend APIs  
- Angular concepts:  
  - Components, Directives, Services  
  - Routing, Route Guards, Auth Guards  
  - Interpolation & Internationalization  
  - Lifecycle Hooks (`ngOnInit`, `constructor`)  
  - Data passing between components (route parameters)  
  - Custom Directives & Pipes  
  - `*ngFor`, `*ngIf` directives  
  - Observables & HttpClient  
  - Session Management

