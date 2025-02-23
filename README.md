# Real-Time Collaborative Document Editor

This is a **real-time collaborative document editing** application built with **Ruby on Rails 7**. The goal is to allow multiple users to edit documents in real-time.

## 🚀 Current Progress

- Initialized a Rails 7 project
- Set up PostgreSQL as the database
- Integrated Devise for user authentication.
- Next Steps: Implement real-time collaboration with AnyCable and integrate React.]

## 🛠️ Tech Stack

- **Backend:** Ruby on Rails 7, PostgreSQL
- **Authentication:** Devise
- **Real-Time:** AnyCable (planned)
- **Containerization:** Docker, Docker Compose
- **Frontend:** React (planned)

## 🔧 Setup Instructions

### Prerequisites

- Ruby 3.0+
- Rails 7+
- PostgreSQL
- Redis
- Docker & Docker Compose (if using Docker)

### 1️⃣ Clone the Repository

git clone https://github.com/SaifuddinSiddique/real_time_collab_app.git
cd real_time_collab_app

### Install Dependencies

bundle install

### Set Up the Database

rails db:create db:migrate

### Start the Server

rails s
