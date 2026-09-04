# 🏆 Sports Tournament Management System

## 📌 Project Overview

The Sports Tournament Management System (STMS) is a database-driven application designed to simplify and automate the management of sports tournaments.

The system provides a centralized platform for managing tournament-related information including users, roles, teams, players, tournaments, matches, and results.

The project was developed as part of the **Advanced Database Management System** course.

---

## 🎯 Objectives

The main objectives of this project are:

- Centralize tournament-related information in a single database.
- Reduce manual work and minimize human errors.
- Maintain accurate and consistent tournament data.
- Manage users based on different roles.
- Manage teams and players.
- Register teams for tournaments.
- Schedule and manage matches.
- Store and manage match results.
- Provide easy access to tournament information.

---

# 👥 User Roles

The system supports the following user roles:

| Role | Responsibility |
|------|---------------|
| System Administrator | Manages users and organizers |
| Tournament Organizer | Creates and manages tournaments |
| Team Captain | Manages teams and players |
| Viewer | Views tournament results |

---

# ⚙️ Key Features

## 🔐 User and Role Management

- User registration and management
- Role-based system
- Multiple phone numbers for users

## 🏆 Tournament Management

- Create tournaments
- Manage tournament information
- Store tournament start and end dates

## 👥 Team Management

- Create and manage teams
- Assign team captains
- Store team coach information

## ⚽ Player Management

- Add players to teams
- Store player information
- Each player belongs to a specific team

## 📅 Match Management

- Schedule matches
- Store match venue
- Store match date and time
- Track match status

## 🥇 Result Management

- Store home team score
- Store away team score
- Maintain match result status

---

# 🗄️ Database Design

The system contains the following main entities:

- Role
- Users
- UserPhone
- Tournament
- Team
- Player
- Match
- Result

The system also contains relationship tables:

- Organize
- Register
- Play
- Views

---

# 📊 Database Relationships

The system supports several important relationships:

- One role can be assigned to multiple users.
- A user can have multiple phone numbers.
- Organizers can manage tournaments.
- Teams can register for multiple tournaments.
- A tournament can contain multiple teams.
- A team contains multiple players.
- A tournament can have multiple matches.
- A match is played by two teams.
- Each match has a result.
- Viewers can view match results.

---

# 📁 Project Structure

```text
Sports-Tournament-Management-System-Oracle
│
├── README.md
│
├── report/
│   └── Project_Report.pdf
│
├── diagrams/
│   ├── Class_Diagram.png
│   ├── Use_Case_Diagram.png
│   ├── Activity_Diagram.png
│   ├── ER_Diagram.png
│   └── Schema_Diagram.png
│
├── database/
│   ├── 01_create_user.sql
│   ├── 02_create_tables.sql
│   ├── 03_insert_data.sql
│   └── 04_verify_database.sql
│
├── queries/
│   ├── basic_plsql/
│   └── advanced_plsql/
│
