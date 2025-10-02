# FinTrack — Personal Finance Tracker

SQL-based finance tracking app for managing transactions, categories, and monthly insights.  
Built as a practice project to demonstrate database-driven applications, reporting, and data visualization.

---

## 🚀 Overview
FinTrack is a console + database project that simulates a personal finance manager.  
It demonstrates how to design relational schemas, implement SQL queries for analytics,  
and build modular code for extensibility.

Key focuses:
- SQL-based persistence with schema normalization
- Aggregate queries for insights (monthly totals, category spending)
- Simple CLI/JavaFX interface
- Data visualization with Chart.js (planned)

---

## 🛠 Tech Stack
- **Backend:** Java 17  
- **Database:** MySQL / PostgreSQL  
- **UI:** CLI (console), JavaFX (optional)  
- **Visualization:** Chart.js (planned)  
- **Practices:** SQL queries, aggregation, reporting, unit testing  

---

## 📂 Features
- Add, update, delete transactions  
- Organize transactions into categories (Food, Rent, Transport, etc.)  
- Generate monthly expense reports  
- Summaries with SQL aggregation queries  
- Basic CLI interface (Java)  
- Planned: visualization with Chart.js  

---

## 📦 Project Structure (planned)
fintrack/
├── src/main/java/com/romankafi/fintrack # Source code
├── src/test/java/com/romankafi/fintrack # Unit tests
├── db/ # SQL schema & sample data
├── pom.xml # Maven build file
└── README.md



---

## 🔧 Setup & Run

Clone repository:
```bash
git clone https://github.com/RomanKAFI/fintrack.git
cd fintrack
Build with Maven:


mvn clean install
Run locally:


mvn exec:java
✅ Roadmap
 Initialize repository with README, license, gitignore

 Design MySQL schema and SQL queries

 Implement Java backend for transaction handling

 Add aggregation queries (monthly/category reports)

 Add JavaFX module for UI

 Integrate Chart.js for visualization

📜 License
MIT License — free to use and modify.
