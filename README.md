# 🎮 Multiplayer Battleground Database Management System

A relational database management system designed for a multiplayer battleground game. The project models various in-game entities such as players, clans, matches, weapons, vehicles, seasons, and rankings while ensuring data consistency through normalization and relational constraints.

---

## 📖 Overview

This project was developed as part of a Database Management Systems course to demonstrate relational database design, normalization, and SQL query optimization.

The database manages player profiles, match statistics, clans, game modes, maps, vehicles, weapons, seasonal rankings, and in-game wallets using a well-structured relational schema.

---

## ✨ Features

- Player profile management
- Clan creation and management
- Match history tracking
- Weapon usage statistics
- Vehicle spawning system
- Seasonal rankings and leaderboards
- Wallet and coin balance management
- Game mode and map management
- Administrator management
- Normalized relational schema with referential integrity

---

## 🛠 Technologies Used

- PostgreSQL
- SQL
- Relational Database Design
- ER Modeling

---

## 📂 Repository Structure

```
battleground-database/
│
├── schema.sql
├── insert.sql
├── queries.sql
└── README.md
```

---

## 📊 Database Modules

The database consists of multiple interconnected entities, including:

- Player
- Clan
- Admin
- Match
- Weapon
- Vehicle
- Map
- Game Mode
- Season
- Wallet
- Rankings
- Participation Records

Relationships are implemented using primary keys, foreign keys, and junction tables to maintain referential integrity.

---

## 🧠 SQL Concepts Demonstrated

- CREATE TABLE
- ALTER TABLE
- PRIMARY KEY
- FOREIGN KEY
- Composite Keys
- INSERT Operations
- INNER JOIN
- Aggregate Functions
- GROUP BY
- ORDER BY
- Nested Queries
- Correlated Subqueries
- Database Normalization

---

## 📈 Sample Queries

The project includes several analytical SQL queries, such as:

- Calculate each player's Kill/Death (K/D) ratio
- Find the winner of every match
- Identify the highest-kill player in each match
- Generate seasonal leaderboards
- Retrieve the top 5 players based on kills
- Calculate average kills per match
- Determine each player's favorite weapon
- Rank players based on weapon accuracy
- Find players with above-average experience
- Rank clans by total player experience
- List vehicles based on maximum speed
- Calculate administrator workload

---

## 🚀 How to Use

1. Create a PostgreSQL database.

2. Execute the table creation script.

```
schema.sql
```

3. Populate the database using

```
insert.sql
```

4. Execute the sample SQL queries from

```
queries.sql
```

5. Refer to the ER diagram and relational schema for database structure.

---

## 📷 Documentation

The repository includes:

- DDL Scripts
- Sample Data
- SQL Query Collection

---

## 🎯 Learning Outcomes

- Relational Database Design
- Database Normalization
- ER Modeling
- Referential Integrity
- Complex SQL Query Writing
- Data Analysis using SQL
- Database Schema Design

---

## 🔮 Future Improvements

- Stored Procedures
- Database Triggers
- Views
- Index Optimization
- User Authentication
- Tournament Management
- Friend System
- Achievement Tracking
- REST API Integration

---
