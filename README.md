Web-Based Port Scanner Manual
PBL-214

Table of Contents
Introduction
System Requirements
Installation
Configuration
Usage
Troubleshooting
FAQ
Contact Information

1. Introduction
Welcome to the Web-Based Port Scanner Manual.
This tool allows you to scan open ports on a specified IP address through a web interface.
It is built using Flask for the backend and JavaScript for the frontend.

2. System Requirements
Python 3.8 or higher

Flask 2.0 or higher

Node.js 14 or higher (for frontend development)

Basic understanding of network protocols and port scanning

3. Installation
Backend
Clone the Repository
git clone https://github.com/your-repo/web-port-scanner.git
cd web-port-scanner
Create a Virtual Environment
python3 -m venv venv
source venv/bin/activate
Install Dependencies

pip install -r requirements.txt
Run the Application
flask run
Frontend

Navigate to the Frontend Directory

cd frontend
Install Dependencies

npm install
Run the Development Server

npm start
4. Configuration
Edit the app.py file to set specific configurations such as:

Allowed IP ranges
Logging preferences
Other custom settings

5. Usage
Access the Web Interface
After running the backend, go to:
http://127.0.0.1:5000

Enter IP Address
Input the target IP address in the provided field.

Select Ports
Choose which ports to scan (can be a range or specific ports).

Start Scan
Click on the "Start Scan" button to begin.
Results will be displayed in the results section.

6. Troubleshooting
Common Issues
Application Not Starting

Make sure all dependencies are installed.

Ensure the virtual environment is activated:
source venv/bin/activate
flask run
Frontend Not Loading

Ensure the Node.js server is running:
cd frontend
npm start
Logs
Check the logs/ directory for error logs and debugging output.
