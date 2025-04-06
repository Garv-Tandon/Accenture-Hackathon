# Accenture-Hackathon
# 🧠 Multi-Agent Hyper-Personalized Product Recommendation System

This project implements a multi-agent AI system to deliver hyper-personalized product recommendations for an e-commerce platform. By simulating **Customer Agents**, **Product Agents**, and **Recommendation Agents**, it mimics a collaborative, scalable framework for improving customer engagement and conversion rates.

---

## 🚀 Features

- 📦 **Customer Agent**: Logs user behavior like viewing, adding to cart, or purchasing.
- 🛍️ **Product Agent**: Retrieves product metadata and stats.
- 🤖 **Recommender Agent**: Uses collaborative filtering logic to suggest products based on behavior of other similar users.
- 🗂️ **SQLite Integration**: Lightweight relational database for persistent long-term memory.
- 📊 **Automatic Recommendations**: Personalized product suggestions based on past activities.
- 🔁 **Simulated User Activity**: Sample interactions demonstrate end-to-end recommendation flow.

---

## 🛠️ Technologies Used

- Python 3.x
- SQLite (for database and long-term memory)
- SQL queries (for data operations)
- Object-based multi-agent simulation

---

## 📁 Project Structure

```bash
.
├── multiagent_system.py       # Core multi-agent simulation and recommender logic
├── multiagent.db              # SQLite database (created at runtime)
└── README.md                  # Project documentation
