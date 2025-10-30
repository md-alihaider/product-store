# 🔥 Product Store (Full-Stack MERN)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.md)
[![GitHub issues](https://img.shields.io/github/issues/md-alihaider/product-store)](https://github.com/md-alihaider/product-store/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/md-alihaider/product-store)](https://github.com/md-alihaider/product-store/pulls)

---
**[ ➡️ LIVE DEMO ⬅️ ](https://product-store-w5dq.onrender.com)**
---

A full-stack MERN application that provides a clean and modern interface for managing a product catalog. This project demonstrates core CRUD (Create, Read, Update, Delete) operations, connecting a React/Chakra UI frontend to a Node.js/Express backend with a MongoDB database.

## 📸 Screenshots

| Main Product View | Create New Product | Update Product Modal |
| :---: | :---: | :---: |
| ![Main product view](<img width="1920" height="1080" alt="Screenshot 2025-10-30 084956" src="https://github.com/user-attachments/assets/418c2b09-cce5-490c-8fc9-09e303ce27ef" />) | ![Create new product form](<img width="1920" height="1020" alt="Screenshot 2025-10-30 085028" src="https://github.com/user-attachments/assets/04769f8c-4491-40e4-869f-b25d96c64adf" />) | ![Update product modal](<img width="1920" height="1020" alt="Screenshot 2025-10-30 085049" src="https://github.com/user-attachments/assets/0dd00586-0dd3-4f0c-b228-1354d77c2e1b" />) |

## ✨ Features

* **Full CRUD Functionality:** Create, Read, Update, and Delete products from the database.
* **View Products:** See all current products in a clean, card-based layout.
* **Add Products:** A dedicated `/create` page with a form to add new products to the catalog.
* **Update Products:** Edit product details (name, price, image) via a clean popup modal.
* **Delete Products:** Instantly remove products from the catalog.
* **Light/Dark Mode:** Toggle between light and dark themes for user comfort, powered by Chakra UI.
* **Responsive Design:** The interface is fully responsive and looks great on all devices.

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Frontend** | [React.js](https://reactjs.org/) |
| **UI Library** | [Chakra UI](https://chakra-ui.com/) |
| **Backend** | [Node.js](https://nodejs.org/) |
| **Server** | [Express.js](https://expressjs.com/) |
| **Database** | [MongoDB](https://www.mongodb.com/) |
| **Deployment**| [Render](https://render.com/) |

## 🚀 Getting Started

To get a local copy of the frontend up and running, follow these steps.

### Prerequisites
* [Node.js](https://nodejs.org/en/) (v16 or newer)
* [npm](https://www.npmjs.com/) (or [yarn](https://yarnpkg.com/))
* A running instance of the backend server.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/md-alihaider/product-store.git](https://github.com/md-alihaider/product-store.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd product-store
    ```
3.  **Install dependencies:**
    ```sh
    npm install
    ```
4.  **Set up environment variables:**
    > [!IMPORTANT]
    > Create a `.env` file in the root of the project and add the URL for your backend API:
    > ```
    > REACT_APP_API_URL="http://localhost:8000"
    > ```
    > *(Update the URL to match your local backend server's address.)*
5.  **Run the development server:**
    ```sh
    npm start
    ```
    The application will be available at `http://localhost:3000`.

## 📄 License

Distributed under the MIT License.

## 🧑‍💻 Author

**Ali Haider**
* GitHub: [@md-alihaider](https://github.com/md-alihaider)
