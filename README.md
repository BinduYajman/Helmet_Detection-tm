# helmet-detection
This was a small project developed within a short form for an ideathon.
🪖 AI-Based Automatic Helmet Alert System

An AI-powered safety system that detects helmet usage in real time using a camera and alerts riders when a helmet is not worn. The solution promotes road safety through proactive, automated enforcement without manual intervention.

Problem Statement

Two-wheeler accidents due to non-helmet usage are a major cause of serious injuries and fatalities. Existing enforcement relies on manual police checks, which are inconsistent and inefficient. There is a need for an automated, real-time solution that ensures helmet compliance without inconveniencing riders.

💡 Solution Overview

This project uses machine learning and computer vision to detect whether a rider is wearing a helmet. A camera captures live video, which is processed by an AI model trained using Google Teachable Machine. Based on the prediction:

✅ Helmet detected → Safe status shown
❌ No helmet detected → Visual warning + buzzer alert

The system runs entirely in the browser using TensorFlow.js.

✨ Features

Real-time helmet detection using AI<br>
Live camera (webcam) input<br>
Automatic classification: Helmet / No Helmet<br>
Visual alerts for safety status<br>
Audio buzzer warning for non-compliance<br>
Browser-based (no special hardware required)<br>
Scalable for smart vehicles and smart helmets<br>

🛠️ Technologies Used<br>

Google Teachable Machine – Model training<br>
TensorFlow.js – Real-time inference in browser<br>
Teachable Machine Image Library<br>
Google Chrome Web APIs (Camera & Audio)<br>
Google Actions Sound Library<br>
HTML5 <br>
JavaScript

⚙️ How It Works (Process Flow)

User starts the system
Camera captures live video frames
AI model analyzes each frame
Helmet status is classified
Alerts are triggered if helmet is not detected
System continuously monitors during the ride

📁 Project Structure

├── index.html

├── README.md

└── (Teachable Machine model loaded via URL)

🔮 Future Enhancements

🔐 Ignition interlock system (vehicle won’t start without helmet) 
🪖 Smart helmet integration with built-in sensors  
🚨 Accident detection using motion sensors  
📍 GPS-based emergency alerts  
📱 Mobile app integration  
☁️ Cloud-based analytics for smart cities

Inspired by industry developments such as TVS Motor Company’s automatic helmet detection connected to vehicle ignition systems. 
