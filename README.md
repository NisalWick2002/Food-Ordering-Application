# Food-Ordering-Application

## Contributors 🏅  

* [Pubudu Perera]( https://github.com/Pamod45)
* [Vishan Perera](https://github.com/VishanPerera)

This extensive project leverages the power of Node.js, Express, MongoDB, React, Docker, and RESTful APIs to create a robust, modular system for efficient food ordering. Designed to handle everything from authentication to delivery tracking, this project streamlines operations, enhancing user experience and productivity.  

---

## Table of Contents 📚  

- [Overview](https://github.com/NisalWick2002/Food-Ordering-Application?tab=readme-ov-file#overview-)
- [Overview](https://github.com/NisalWick2002/Food-Ordering-Application?tab=readme-ov-file#objectives-)
- [Overview](https://github.com/NisalWick2002/Food-Ordering-Application?tab=readme-ov-file#microservices-and-endpoints-)
- [Overview](https://github.com/NisalWick2002/Food-Ordering-Application?tab=readme-ov-file#contributions-)
- [Overview](https://github.com/NisalWick2002/Food-Ordering-Application?tab=readme-ov-file#license-)
  
---

## Overview 📋  

This **Food Ordering Application** provides a comprehensive solution for managing the entire lifecycle of food orders. The project is divided into five distinct microservices, each handling specific aspects of the system. By employing modular and scalable architecture, this application ensures seamless integration and robust performance under high demand.  

With user authentication, menu management, order processing, and delivery tracking, this platform is tailored to meet the dynamic needs of modern food ordering businesses.  

---

## Objectives 🎯  

- **Streamline food ordering and delivery processes** by integrating multiple features into a unified system.  
- **Enhance user experience** with a responsive, user-friendly interface and real-time updates on order status.  
- **Ensure security and scalability** using best practices in authentication and API design.  
- **Provide flexibility** to add, update, and remove menu items and categories dynamically.  
- **Facilitate efficient delivery management** with real-time delivery tracking and assignment systems.  
- **Optimize backend operations** for admins to monitor and update orders seamlessly.  

---

## Microservices and Endpoints 🔧  

This project is divided into five core microservices:  

### Authentication and User Management Microservice  
Handles user registration, login, and profile management.  

- **Endpoints**:  
  - `/register`: Register a new user.  
  - `/login`: Authenticate a user.  
  - `/logout`: Log out the user.  
  - `/reset-password`: Reset the user password.  

### Menu Management Microservice  
Manages categories and items in the menu.  

- **Endpoints**:  
  - `/menus`: Manage menu categories.  
  - `/menus/{id}/items`: Associate items with categories.  

### Item Management Microservice  
Handles creation and modification of menu items.  

- **Endpoints**:  
  - `/items`: Add, update, or delete menu items.  
  - `/items/{id}`: Retrieve item details.  

### Order Management Microservice  
Manages order processing and status updates.  

- **Endpoints**:  
  - `/orders`: Create and manage customer orders.  
  - `/orders/{id}`: View or update specific orders.  

### Delivery Management Microservice  
Tracks deliveries and assigns them to delivery personnel.  

- **Endpoints**:  
  - `/deliveries`: Manage delivery tasks.  
  - `/deliveries/{id}`: View delivery details.  

---

## Contributions ✨  

We welcome contributions to improve this project!  
- Submit issues or pull requests to suggest improvements or fix bugs.  
- For major changes, open an issue to discuss your ideas before implementation.  

---

## License 📜  

This project is licensed under the [MIT License](LICENSE).  

---
