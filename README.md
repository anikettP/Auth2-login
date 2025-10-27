Live Link - [Bookztron](https://bookztron-dev-branch.netlify.app/)

# 📚 Book Store – Spring Boot + Thymeleaf Project

A full-stack **Book Store Web Application** built using **Spring Boot**, **Thymeleaf**, **AdminLTE**, and **PostgreSQL**.  
It provides user authentication, dynamic book listing, sorting/filtering, cart & wishlist management, and secure order processing.

---

## 🚀 Getting Started

### ▶️ Run the Project

```bash
mvn spring-boot:run
Then open http://localhost:8080
 in your browser.
The page will reload automatically when you make changes (if using spring-boot-devtools).
🛠️ Tech Stack
🧩 Frontend
HTML5
CSS3
JavaScript (ES6)
Thymeleaf (Template Engine)
AdminLTE (Responsive Admin Dashboard Template)
⚙️ Backend
Spring Boot
Spring MVC
Spring Data JPA
Spring Security (for Authentication & Authorization)
🗄️ Database
PostgreSQL / MySQL
☁️ Deployment
Deployed on Render, Vercel, or Railway
✨ Features
👤 User Authentication
Signup, Login, Logout using Spring Security
Role-based access (Admin / User)
🏠 Landing Page
Dynamic landing page with categories and new arrivals
Category-based browsing and book recommendations
📚 Product (Book) Management
Display all books with pagination
Sort books by:
Price (Low → High / High → Low)
Filter by:
Minimum and Maximum Price Range
Book Genre
Average Rating
Availability (In Stock / Out of Stock)
Fast Delivery Option
Clear all filters easily
❤️ Wishlist Management
Add / Remove books from Wishlist
Add to Cart directly from Wishlist
🛒 Cart Management
Add Books to Cart
Increase/Decrease Quantity
Remove Items from Cart
Move Items to Wishlist
Apply Discount Coupons
📄 Single Product Page
Detailed book information (author, rating, description)
Related books section
💳 Order and Payment
Secure Payment Integration (Razorpay / Stripe / Paytm)
Order Summary after checkout
Order history in user profile
🔔 Notifications
Custom Toast messages for:
✅ Success
⚠️ Warning
❌ Error
ℹ️ Info
🔍 Search & Pagination
Book_store/
│
├── src/
│   ├── main/
│   │   ├── java/com/bookstore/
│   │   │   ├── controller/     # All controllers
│   │   │   ├── model/          # JPA entities
│   │   │   ├── repository/     # Spring Data JPA repositories
│   │   │   └── service/        # Business logic
│   │   └── resources/
│   │       ├── templates/      # Thymeleaf HTML templates
│   │       ├── static/         # CSS, JS, Images
│   │       └── application.properties
│   └── test/                   # Unit and Integration Tests
│
├── pom.xml                     # Maven dependencies
└── README.md                   # Project Documentation
spring.datasource.url=jdbc:postgresql://localhost:5432/bookstore
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
razorpay.key_id=your_razorpay_key
razorpay.key_secret=your_razorpay_secret

Search books by Title or Author

Pagination for better navigation through large data
