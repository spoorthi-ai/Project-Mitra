MITRA: Multi-Terrain Agricultural Bot 🚜🌾
Affiliation: 4i Labs, Indian Institute of Technology (IIT) Guwahati Status: Pilot Phase (Ongoing)

📖 Overview
MITRA is an AI-powered autonomous agricultural robot designed to solve the labor-intensive problem of manual weeding. Developed at 4i Labs, IIT Guwahati, this system integrates cutting-edge computer vision with robust hardware to differentiate between crops and weeds in real-time, enabling targeted, autonomous removal.

The system is currently in pilot runs at partner farms, where it has demonstrated the ability to reduce manual labor requirements significantly while maintaining high precision in crop safety.

✨ Key Features

Real-Time Weed Detection: Utilizes a fine-tuned YOLOv8 object detection model to distinguish between sesame crops and weeds with high accuracy.


Autonomous Navigation & Action: Capable of autonomous weed removal, covering up to 1 acre/hour.


Edge Computing: Powered by an Jetson Xavier and custom Arduino boards for low-latency processing (<500ms per image).


Smart Farmer Dashboard: A Flask-based web interface (implied from prior discussions) that allows farmers to monitor the bot's status and intervene in real-time.
+1


AI Assistant: Integrated LLM-powered question-answering system for onsite agricultural support.
+1

🛠️ Tech Stack
Software
Core Logic: Python, C++


Computer Vision: YOLOv8 (Fine-tuned on custom datasets) 

Web Interface: Flask (Web App), React (Dashboard)

OS: Ubuntu/Linux (ROS-compatible environment)

Hardware

Compute: Intel NUC (Edge Processing) 


Microcontroller: Custom Arduino Board (Motor control & actuation) 

Chassis: Multi-terrain rover design capable of traversing uneven agricultural fields.

📊 Performance Metrics

Precision: 93.7% 
+2


F1 Score: 92% 


Inference Speed: <500ms per image 


Labor Efficiency: Reduced manual weeding hours by 60% in initial trials.
+1


Uptime: Successfully field-tested by 5+ farmers.

🚀 Installation & Setup
Clone the repository

Bash

git clone https://github.com/4ilabiitg/MITRA-Multi-Terrain-Agricultural-Bot.git
cd MITRA-Multi-Terrain-Agricultural-Bot
Install Dependencies

Bash

pip install -r requirements.txt
Run the Inference Module

Bash

python src/inference.py --source 0  # Webcams or video file
Launch Dashboard

Bash

cd web-app
flask run
👥 Team & Contributors
This project was developed by a 12-member interdisciplinary team at 4i Labs, IIT Guwahati.


Project Lead: Aryan 

Mentors & Faculty: 4i Labs Faculty Advisors



Field Deployment: Successfully moved from concept to field deployment in under 4 months.


Adoption: Currently adopted for pilot runs at 2 partner farms
