# LifeQuest

LifeQuest is a Java-based habit and skill tracking RPG that turns everyday tasks into quests.

Users can create and complete quests, earn XP, level up, track their progress, and manage their character stats. The project is designed as a college-level Object-Oriented Programming project using Java Swing, JDBC, and MySQL.

## Project Overview

The main idea of LifeQuest is to make everyday productivity more engaging through a simple RPG-style system.

Instead of simply maintaining a to-do list, users complete quests and receive XP based on the difficulty of the task.

### Core Flow

Create Quest
↓
Complete Quest
↓
Earn XP
↓
Check Level
↓
Level Up
↓
Update Character & Progress
↓
View History / Analytics

## Features

- User registration and login
- Dashboard with level and XP progress
- Create and manage quests
- Quest categories, priorities and difficulty levels
- Repeatable quests
- XP-based progression system
- Character stats
- Quest completion history
- Basic analytics and weekly progress
- Achievements
- Profile management
- Dark mode
- Notification preference
- Reset progress
- Logout

## XP System

| Difficulty | XP |
|------------|----|
| Easy       | 20 |
| Medium     | 50 |
| Hard       | 80 |
| Epic       | 120 |

Priority and difficulty are treated as separate properties of a quest.

## Technology Stack

- **Language:** Java
- **GUI:** Java Swing
- **Database:** MySQL
- **Database Connectivity:** JDBC
- **Build Tool:** Maven
- **Version Control:** Git & GitHub
- **IDE:** VS Code / IntelliJ IDEA / Eclipse

## Project Structure

```text
LifeQuest/
├── pom.xml
├── database.sql
├── README.md
└── src/
    └── main/
        └── java/
            └── lifequest/
                ├── Main.java
                ├── model/
                │   └── User.java
                ├── database/
                │   ├── DB.java
                │   ├── UserDAO.java
                │   └── QuestDAO.java
                ├── auth/
                │   ├── LoginPanel.java
                │   └── RegisterPanel.java
                ├── dashboard/
                │   └── DashboardPanel.java
                ├── quests/
                │   ├── QuestPanel.java
                │   └── CreateQuestDialog.java
                ├── history/
                │   └── HistoryPanel.java
                ├── analytics/
                │   └── AnalyticsPanel.java
                ├── profile/
                │   └── ProfilePanel.java
                ├── settings/
                │   └── SettingsPanel.java
                └── ui/
                    └── Style.java