# 🛍️  xmart 

**A modern and intuitive e-commerce platform built with React (frontend) and Spring Boot (backend).**

## ✨ Features

* **Browse Products:** Discover a wide range of products intuitively categorized.
* **Product Details:** View detailed information, images, and reviews for each product.
* **Add to Cart:** Easily add items to your shopping cart for purchase.
* **Secure Checkout:** Experience a secure and streamlined checkout process.
* **Admin Dashboard (Coming Soon):** Manage products, inventory, orders, and more.

## 🚀 Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### 📋 Prerequisites

Make sure you have the following software installed on your system:

* **Node.js and npm:**  [https://nodejs.org/](https://nodejs.org/)
* **Java Development Kit (JDK):**  [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
* **Maven:** [https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi)
* **Git:** (Optional if you want to clone the repository) [https://git-scm.com/downloads](https://git-scm.com/downloads)
* **Your favorite IDE:** We recommend IntelliJ IDEA for the backend (Spring Boot) and VS Code for the frontend (React).

### 📥 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/xmart.git
   cd xmart
   ```

2. **Backend (Spring Boot):**
   * Open the `backend` directory in your IDE.
   * Navigate to the `EcomProjApplication.java` file and run it. Your backend server will typically start on  `http://localhost:8080/`.

3. **Frontend (React):**
   * Open the `frontend` directory in your terminal.
   * Install dependencies: 
      ```bash
      npm install 
      ```
   * Start the development server:
      ```bash
      npm run dev
      ```
   * Your frontend will usually run on `http://localhost:5173/`.

### 🧪 Running the Application

* Once both the backend and frontend servers are running, you can access the application in your web browser at  `http://localhost:5173/`.

## 📂 Project Structure

Here's an overview of the project structure:

```
xmart/
├── backend/          # Spring Boot backend application
│   └── src/main/java/com/telusko/ecom_proj/ 
│       ├── controller/    # REST Controllers
│       ├── model/         # Data Models (Entities)
│       ├── repo/          # Data Repositories (JPA)
│       └── service/       # Business logic
├── frontend/         # React frontend application
│   └── src/ 
│       ├── components/     # Reusable React components
│       └── App.jsx         # Main application component
├── README.md          # This README file
└── ...                # Other configuration files (e.g., pom.xml, package.json)
```

## 🤝 Contributing

Pull requests are welcome!  For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## 🙏  Acknowledgments

* Inspiration from other great e-commerce platforms. 
* Thanks to the open-source community for amazing tools and libraries.

---

**Happy shopping!** 😄