# Phishing-Awareness-Simulation-Lab

📌 Overview

This project is a phishing awareness simulation platform built in a controlled Kali Linux environment. It demonstrates how phishing campaigns operate while focusing on defensive security, user awareness, and behavior analysis.

The system generates unique tracking links, simulates user interactions, and logs activity such as IP addresses and user agents into a database. A dashboard is provided to analyze user behavior and campaign performance.

🎯 Objectives
Simulate phishing attack scenarios in a safe lab environment
Track and analyze user interaction with phishing links
Build hands-on experience with SOC-level monitoring systems
Demonstrate secure and ethical cybersecurity practices
🧠 Features
🔗 Token-Based Tracking Links
Each user is assigned a unique token to simulate individualized phishing links.
👥 User & Campaign Management
Supports multiple users and campaign-based tracking.
📊 Click Tracking & Logging
Logs:
IP Address
User Agent
Timestamp
Campaign ID
🌐 Flask Web Server
Handles tracking endpoints and serves training pages.
🗄️ SQLite Database
Stores users, campaigns, and click data.
📈 Dashboard Analytics
Displays click activity per user for analysis.
⚠️ Security Awareness Training Page
Educates users after interaction with simulated phishing links.
🏗️ Architecture
User Generator → Tokenized Links → Flask Server → SQLite Database → Dashboard

⚙️ Technologies Used
Python 3
Flask (Web Framework)
SQLite (Database)
HTML (Templates)
Kali Linux (Environment)
🚀 Setup Instructions
1. Clone Repository
git clone <your-repo-link>
cd phishing-lab

2. Create Virtual Environment
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install flask requests

4. Run Application
python3 app.py

5. Generate Simulation Links
python3 generator.py

🧪 Usage
Generate unique tracking links for simulated users
Open links in browser or simulate clicks via script
System logs all interactions in database
View results on dashboard:
http://127.0.0.1:8080/dashboard

📊 Example Output
User Email	Clicks
john@lab.local
	2
sarah@lab.local
	1
⚠️ Ethical Considerations

This project is strictly for:

✅ Educational purposes
✅ Controlled lab environments
✅ Cybersecurity training

It must NOT be used for real phishing attacks or unauthorized tracking.

🔮 Future Improvements
🔐 Admin authentication system
📈 Advanced analytics (charts & trends)
🧠 Risk scoring engine
🌍 IP geolocation tracking
🎨 Modern dashboard UI
