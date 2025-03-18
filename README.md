# websiteproject
Build web by scratch with React and Fastapi

# 📌 Project Setup Guide

## 🚀 Clone the Repository
First, clone the repository to your local machine:
```bash
git clone https://github.com/ezoa/websiteproject.git
cd websiteproject
```

## 🐳 Install Docker
Ensure you have **Docker** installed on your system. If not, download and install it from [Docker's official website](https://www.docker.com/).

Verify your installation:
```bash
docker --version
```

## 🏗️ Start MongoDB Database
Start a **MongoDB** instance using Docker:
```bash
docker compose up 
```

## 🔗 Connect to MongoDB
Open new terminal 
Once the database is running, connect using **mongosh**:
```bash
mongosh "mongodb://user:pass@localhost:27019/?directConnection=true"
```

## 📂 View Available Databases
To check if the database is properly set up, run:
```bash
show dbs
```



