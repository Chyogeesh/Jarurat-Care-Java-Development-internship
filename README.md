# Jarurat-Care-Java-Development-internship
It is an internship assignment
WhatsApp Chatbot Project
Overview
A Spring Boot-based WhatsApp chatbot for a navigation program, integrating Firebase for chat history and deployed on Render. This project demonstrates backend development skills with Java, RESTful APIs, and third-party service integration.
Tech Stack

Language: Java
Framework: Spring Boot
Database: Firebase (Firestore)
Deployment: Render
API: Meta WhatsApp Business API (mocked)

Setup Instructions

Clone the repository:git clone https://github.com/yourusername/whatsapp-chatbot.git
cd whatsapp-chatbot


Configure Firebase:
Download service-account.json from Firebase Console and place it in src/main/resources.
Update application.properties with your Firebase URL and WhatsApp API credentials.


Build the project:./mvnw clean install


Run locally:./mvnw spring-boot:run


Deploy to Render:
Push to GitHub and connect to Render.
Use render.yaml for configuration.



API Endpoints

POST /api/chat/receive: Receive and process WhatsApp messages.

Notes

Replace placeholder URLs and tokens in application.properties with actual values.
Mock WhatsApp API call needs to be replaced with a real HTTP client (e.g., RestTemplate or WebClient).
Ensure Firebase setup is complete before deployment.

Deployment

Live URL: [To be added after Render deployment]
GitHub Repository: [https://github.com/yourusername/whatsapp-chatbot]
whatsapp-chatbot/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── whatsappchatbot/
│   │   │   │   │   ├── config/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── model/
│   │   │   │   │   ├── service/
│   │   │   │   │   ├── WhatsAppChatbotApplication.java
│   │   ├── resources/
│   │   │   ├── application.properties
│   ├── test/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── whatsappchatbot/
│   │   │   │   │   ├── controller/
│   │   │   │   │   ├── service/
├── render.yaml
├── README.md
