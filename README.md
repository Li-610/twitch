# Twitch+
A personalized Twitch resource recommendation engine built with Spring Boot and React. The system integrates Twitch APIs and provides users with tailored streamer recommendations based on their preferences.

## Features
- Optimized backend with Spring Boot and OpenFeign for efficient Twitch API integration
- Content-based recommendation algorithm based on user behavior
- Responsive and user-friendly UI built with React and Ant Design
- 🛡Secure authentication and authorization using Spring Security
- 🗄Data stored in MySQL and deployed on AWS RDS

## Tech Stack
- Backend: Spring Boot, OpenFeign, Spring Security, MySQL (AWS RDS)
- Frontend: React, Ant Design
- Others: REST API, AWS EC2, Git

## Getting Started
### Prerequisites
- Java 17+
- Node.js & npm
- MySQL
- Twitch Developer API credentials

### Backend Setup
```bash
cd backend
./gradlew build
java -jar build/libs/twitchplus.jar
