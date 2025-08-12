# Property and Vehicle Damage Verification System

This is a mini project I built to solve a real-world problem using AI and web technologies. It helps in analyzing images of damaged vehicles or properties and gives an estimated repair cost along with a detailed report. The main use case is for insurance claim processing where time, accuracy, and fraud detection are critical.


## Project Objective

The goal of this project is to automate the process of damage verification using artificial intelligence. Users can upload images of damaged property or vehicles, and the system detects the damaged areas, estimates the repair cost, and provides a detailed PDF report with a GPT-generated natural language summary.



## Features

- Upload images of damaged vehicles or property
- AI-powered damage detection using Roboflow
- Automatic repair cost estimation based on damage type and severity
- PDF report generation including image, cost, and summary
- Natural language explanation of damage using GPT
- Simple and clean user interface using Streamlit
- Flask-based backend for processing and integration



## Tech Stack Used

- **Frontend:** Streamlit, HTML, CSS (for some parts)
- **Backend:** Python, Flask
- **Image Processing & Damage Detection:** Roboflow, OpenCV
- **Natural Language Generation:** OpenAI GPT API
- **Report Generation:** ReportLab
- **Environment Variables:** `.env` file for storing API keys
- **Version Control:** Git & GitHub



## Problem Statement

In traditional insurance claim processes, damage verification is done manually, which is time-consuming and error-prone. Customers need to submit pictures and wait for someone to assess the damage, often leading to delays and inaccurate cost estimation. 

This project aims to:
- Automate the claim verification process
- Detect and analyze damage using AI
- Provide instant cost estimation and reporting
- Reduce manual work and fraud chances



## Target Users

- Insurance companies and agents
- Vehicle owners submitting insurance claims
- Property owners claiming damage reimbursement
- Claim verification departments
