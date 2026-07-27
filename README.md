# 🍔 FoodBot Pro – AI-Powered Food Delivery Chatbot

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Database](https://img.shields.io/badge/Database-SQLite-green)
![Architecture](https://img.shields.io/badge/Architecture-Modular-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Overview

FoodBot Pro is an AI-powered food delivery chatbot developed to simulate a real-world food ordering system through a conversational interface. The application enables users to place food orders, retrieve order details, track deliveries, and interact with restaurant data using natural language.

The project follows a modular architecture that separates conversation handling, orchestration, database operations, and SQL query execution, making the system scalable and easier to maintain. The SQL Agent acts as the bridge between the chatbot and the database by retrieving and formatting order information for user-friendly responses. 

---

# 🚀 Features

- 🤖 AI-powered conversational food ordering
- 🍕 Food order management
- 🚚 Order tracking
- 🗄️ Database integration
- 🔍 SQL Agent for data retrieval
- 📄 Human-readable response formatting
- ⚡ Efficient database queries
- 🏗️ Modular software architecture
- 🧩 Object-Oriented Programming (OOP)
- 🛡️ Secure and structured data access

---

# 🏛️ System Architecture

The chatbot follows a layered architecture where each component has a dedicated responsibility.

```
User
   │
   ▼
Conversation Layer
   │
   ▼
Orchestration Agent
   │
   ▼
SQL Agent
   │
   ▼
Database Manager
   │
   ▼
SQLite Database
```

The architecture separates business logic from database operations, improving maintainability and supporting future scalability. 

---

# 🧠 Core Components

### Database Manager
- Manages database connections
- Executes SQL queries
- Handles transactions

### SQL Agent
- Retrieves order information
- Formats database records into readable responses
- Acts as the data access layer

### Order Controller
- Coordinates business logic
- Combines SQL Agent responses
- Manages user requests

### Chatbot Orchestrator
- Processes user intent
- Routes requests
- Coordinates system components

These responsibilities are described in the project architecture documentation. 

---

# 💻 Technologies Used

- Python
- SQLite
- SQL
- Object-Oriented Programming (OOP)
- Jupyter Notebook

---

# 📂 Project Structure

```
FoodBot-Pro
│
├── README.md
├── assets/
├── docs/
│   └── FoodBot_Report.pdf
├── notebooks/
│   └── FoodBot_Development.ipynb
└── src/
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/FoodBot-Pro.git
```

Navigate to the project

```bash
cd FoodBot-Pro
```

Launch the Jupyter Notebook

```bash
jupyter notebook
```

Open

```
FoodBot_Development.ipynb
```

Run all cells.

---

# 📊 Database Schema

The chatbot stores order-related information including:

- Order ID
- Customer ID
- Restaurant ID
- Order Status
- Delivery Address
- Payment Method
- Estimated Arrival
- Order Timestamp

The SQL Agent dynamically retrieves and formats these fields without requiring changes when new columns are added. 

---

# 🔒 Security Considerations

The project incorporates several backend security practices:

- Parameterized SQL queries
- Input validation
- Layered architecture
- Separation of business logic and database access

The accompanying documentation also recommends authentication, rate limiting, audit logging, and protection of personally identifiable information before exposing data through the chatbot interface. 

---

# 📈 Future Improvements

- Web interface
- Voice-enabled chatbot
- LLM integration
- Restaurant recommendations
- Online payment support
- Cloud database deployment
- Multi-user authentication
- Docker deployment

---

# 📚 Documentation

Detailed technical documentation is available in the **docs/** directory.

It includes:

- System Architecture
- SQL Agent Design
- Database Schema
- Performance Analysis
- API Integration
- Security Considerations
- Deployment Roadmap



---

# 👨‍💻 Author

**Paras Attri**

AI & Machine Learning Graduate  
Python | Machine Learning | Data Analysis | SQL | AI Applications

LinkedIn: *(Add your profile)*

GitHub: *(Add your profile)*

---

## ⭐ If you found this project interesting, consider giving it a Star!
