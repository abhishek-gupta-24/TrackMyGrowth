# Track My Growth

This project tracks a user's problem-solving and rating statistics across platforms like Codeforces, LeetCode, GFG, and CodeChef.

## Repositories
- [Frontend](https://github.com/abhishek-gupta-24/TrackMyGrowth-Frontend.git)
- [Backend](https://github.com/abhishek-gupta-24/TrackMyGrowth-Backend.git)

## Tech Stack
React, TailwindCSS, Node.js, Express.js, MongoDB, bcrypt.js


##Architecture of Project
<img width="1348" height="849" alt="image" src="https://github.com/user-attachments/assets/68fa19bb-47de-49bb-8354-fc9a0b98b18b" />
# TrackMyGrowth - Full-Stack Goal Tracking Application 🚀

Welcome to TrackMyGrowth, a complete full-stack application designed to help users set, manage, and achieve their personal and professional goals. This project combines a modern, responsive frontend with a robust and secure backend API.

---

## ✨ Key Features

* **🔐 Secure User Authentication:** End-to-end user registration and login system using JWT for stateless, secure sessions.
* **🎯 Full Goal Management:** A complete CRUD (Create, Read, Update, Delete) interface for managing goals.
* **📊 Interactive Dashboard:** A central hub to view all goals and track progress at a glance.
* **📈 Progress Visualization:** Modern charts and graphs to visually represent your journey and achievements over time.
* **📱 Responsive Design:** A seamless user experience across all devices, from desktops to mobile phones.
* **✅ RESTful API:** A well-structured and documented API to ensure clear communication between the client and server.

---

## 🏗️ Architecture Overview

This project follows a classic client-server model. The frontend is a single-page application (SPA) that communicates with a backend RESTful API. The API handles all business logic, data persistence, and user authentication.



* **Frontend:** The user interface built with `[e.g., React]`. It makes HTTP requests to the backend API to fetch and manipulate data.
* **Backend:** The server built with `[e.g., Java & Spring Boot]`. It exposes a REST API, connects to the database, and manages all core functionalities.
* **Database:** A `[e.g., MongoDB]` database to persist all user and goal data.

---

### Backend

* **Language:** `[e.g., Java 11]`
* **Framework:** `[e.g., Spring Boot]`
* **Database:** `[e.g., MongoDB]`
* **Authentication:** `[e.g., Spring Security with JWT]`
* **Build Tool:** `[e.g., Maven]`

---

## ⚙️ Local Development Setup

Follow these steps to get the entire application running on your local machine.

### Prerequisites

* **Node.js & npm:** For running the frontend.
* **JDK & Maven:** For running the backend.
* **Git:** For cloning the repositories.
* **MongoDB:** A running instance of the database.

### Installation & Setup

1.  **Create a main project directory and clone both repositories:**
    ```sh
    mkdir TrackMyGrowth
    cd TrackMyGrowth
    git clone [https://github.com/abhishek-gupta-24/TrackMyGrowth-Backend.git](https://github.com/abhishek-gupta-24/TrackMyGrowth-Backend.git)
    git clone [https://github.com/abhishek-gupta-24/TrackMyGrowth-Frontend.git](https://github.com/abhishek-gupta-24/TrackMyGrowth-Frontend.git)
    ```

2.  **Set up and run the Backend:**
    * Navigate to the backend directory: `cd TrackMyGrowth-Backend`
    * Configure your database and JWT secret in `src/main/resources/application.properties`.
    * Install dependencies and run the server (this will start on port `8080`):
        ```sh
        mvn clean install
        mvn spring-boot:run
        ```
    * **Keep this terminal window open.**

3.  **Set up and run the Frontend (in a new terminal):**
    * Navigate to the frontend directory: `cd TrackMyGrowth-Frontend`
    * Create a `.env.local` file and add the API URL:
        ```
        REACT_APP_API_URL=http://localhost:8080/api
        ```
    * Install dependencies and start the development server (this will open on port `3000`):
        ```sh
        npm install
        npm start
        ```

4.  **You're all set!**
    * 🚀 Your frontend application is now running at **`http://localhost:3000`**.
    * 📡 Your backend API is running at **`http://localhost:8080`**.

---

## 📖 API Documentation

The backend includes interactive API documentation. Once the backend server is running, you can access the Swagger UI at:
**`http://localhost:8080/swagger-ui.html`**

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve TrackMyGrowth, please follow these steps:

1.  Fork the repository you wish to change (Frontend or Backend).
2.  Create a new feature branch (`git checkout -b feature/AmazingFeature`).
3.  Make your changes and commit them (`git commit -m 'Add some AmazingFeature'`).
4.  Push your changes to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file in each repository for more details.

---

## 📧 Contact

Ajay Singh - `[ajaypatel808131@gmail.com]`
