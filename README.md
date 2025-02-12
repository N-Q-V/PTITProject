# **Hybrid Recommendation System for E-Commerce Bookstore**  

## **Overview**  
The **Hybrid Recommendation System** is an AI-powered solution designed to enhance book recommendations in an e-commerce bookstore. It integrates **Collaborative Filtering (CF)** and **Content-Based Filtering (CB)** to optimize personalization and user engagement.  

## **Features**  

### **Hybrid Recommendation Engine:**  
- **Weighted Hybrid:** Combines CF and CB scores with weight for balanced recommendations.  
- **Switching Model:** Dynamically selects CF or CB based on predefined conditions.  
- **Combing Model:** Combines CF and CB scores for balanced recommendations. 

### **Book Catalog Management:**  
- CRUD operations for books and metadata.

### **Reviews & Ratings:**  
- Users can provide ratings and reviews.

### **Analytics Dashboard:**  
- Provides insights into sales performance, user ratings, and revenue trends.
### **Admin Panel:**  
- Manage users, books, and system configurations.  

---

## **Tech Stack & Repository Structure**  

The system is modularized into separate branches in the repository, ensuring better maintainability and scalability.  

### **Backend:**  
- **Technology:** .NET Web API (C#), Entity Framework  
- **Branch:** `BE_api`  
- **Description:**  
  - Handles RESTful API development for book management, user management, and recommendation processing.  
  - Integrates with the database using **Entity Framework** for efficient data handling.  

### **Frontend:**  
- **Technology:** ReactJS  
- **Branch:** `FE_System`  
- **Description:**  
  - Provides an interactive user interface for browsing books, receiving recommendations, and managing profiles.  
  - Connects to the backend via RESTful APIs for seamless data exchange.  

### **Hybrid Recommendation System:**  
- **Technology:** Flask (Python), Scikit-Learn (TF-IDF, Cosine Similarity,Onehot Encoding)  
- **Branch:** `RC_System`  
- **Description:**  
  - Implements **Content-Based Filtering (CB)** using **TF-IDF & Cosine Similarity**.  
  - Implements **Collaborative Filtering (CF)** models (User-Based & Item-Based).  
  - Supports **hybrid recommendation strategies** (Weighted, Switching, Combing).  
  - Exposes recommendation services via **Flask API**, which the backend consumes.  

