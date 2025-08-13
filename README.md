# MANAAHI
"Khuda yaha naa daale" – AI-Powered Violation Detection & Automated Challan System
📖 Overview
MANAAHI is an AI-based surveillance system that leverages CCTV footage, facial recognition, and government-approved ID databases to automatically detect public violations (e.g., littering) and issue digital challans.

The system is designed to:

Detect violations in real time

Identify the violator using face recognition

Generate a challan with relevant details

Send an SMS notification to the violator’s registered mobile number

This project demonstrates how computer vision and automation can be used for smart governance, cleanliness drives, and law enforcement.

🔄 Workflow
Capture Footage from CCTV streams.
Face Detection & Recognition using AI models.
Database Matching with Aadhaar/Government ID photo records.
Violation Detection (e.g., littering).
Challan Generation with timestamp and violation type.
SMS Dispatch to violator via API.

✨ Key Features
🖼 Real-Time Face Detection & Recognition from CCTV feeds
📚 Integration with Government ID Databases for accurate identification
⚡ Automated Violation Detection for littering and similar offenses
📩 Instant SMS Notifications with challan details
🗃 Violation Log Management for audit and reporting
🔐 Secure Data Handling with encrypted storage options

🛠 Tech Stack
Language: Python 3.x
Computer Vision: OpenCV, face_recognition
Data Processing: NumPy, Pandas
Database: SQLite / PostgreSQL

📌 Example Scenario
CCTV detects a person throwing garbage on the road.

System captures the face, matches it with Aadhaar photo.

Generates a challan of ₹500 with violation details.

Sends SMS:

arduino
Copy
Edit
"Challan No: 10234 | ₹500 for public littering | Pay by 25/08/2025."
🔮 Future Enhancements
Multi-violation detection (jaywalking, helmet-less driving, smoking in public).

Automated payment gateway integration.

Integration with municipal databases for direct challan processing.

AI activity recognition for higher accuracy.



SMS API: Twilio / Fast2SMS

Other: JSON for configuration management
