# Qilin

## LFT: League Finder & Team Builder

<p align="center">
  <img src="https://github.com/user-attachments/assets/358e87fd-8247-4b56-81c4-4bda97e2b847" alt="Qilin Logo" width="200">
</p>

LFT revolutionizes team formation in competitive gaming. Our platform seamlessly connects players based on skill level, recent performance, and compatibility, using advanced algorithms.

## Description

LFT empowers gamers to find their ideal teammates through:

- Precision matchmaking based on rank and recent match history
- Detailed player profiles with performance analytics
- Real-time chat for instant communication
- Premium features including voice/video chat and enhanced stats tracking
- Innovative team chemistry analysis for premium members

Whether you're climbing the competitive ladder or seeking casual teammates, LFT provides the tools to elevate your gaming experience. Join us in redefining how gamers connect, compete, and succeed together.

## Table of Contents

- [Individual Contribution](#individual-contribution)
- [Technologies Used](#technologies-used)
- [Usage](#how-to-run)
- [Contributors](#contributors)

## Technologies Used

- **NestJS**: A progressive Node.js framework for building efficient and scalable server-side applications.
- **Prisma**: An ORM (Object-Relational Mapping) tool that simplifies database access and management.
- **MongoDB**: A NoSQL database that provides a flexible and scalable solution for storing application data.
- **JWT (JSON Web Tokens)**: A compact, URL-safe means of representing claims to be transferred between two parties, used for authentication.
- **WebSocket**: A protocol for full-duplex communication channels over a single TCP connection, enabling real-time data transfer.
- **Socket.io**: A library that enables real-time, bidirectional communication between web clients and servers.
- **Stripe API**: A payment processing platform that allows for secure and reliable online transactions.
- **React.js**: A JavaScript library for building user interfaces, particularly for single-page applications.
- **Tailwind CSS**: A utility-first CSS framework for creating custom designs without leaving your HTML.
- **Redis**: An in-memory data store used for caching and managing real-time data efficiently.
- **Riot Games API**: An API that provides access to gaming data, allowing integration of game-related features.
- **Next.js**: A React framework that enables server-side rendering and static site generation for improved performance.
- **Turborepo**: A high-performance build system for JavaScript and TypeScript monorepos.
- **Docker**: A platform designed to help developers build, share, and run container applications.

## Individual Contribution

#### Suvan Sarkar

- Implemented Prisma as the ORM (Object-Relational Mapping) tool to simplify database access and management.
- Set up MongoDB as the database solution to store and retrieve application data in a flexible, scalable manner.
- Designed and developed the database models using Prisma to define the schema and relationships between entities.
- Integrated the Riot Games API to fetch and utilize relevant gaming data within the application.
- Structured the backend architecture to ensure modularity, separation of concerns, and maintainability.
- Utilized NestJS for building the backend application, ensuring a clean and organized code structure.
- Implemented Matchmaking page (for users to connect with players).
- Implemented CI/CD pipeline for automated testing and deployment.
- Set up and configured Docker for containerization of the application.
- Developed and implemented unit testing strategies to ensure code quality.

#### Chaitanya Sikakolu

- Developed a secure login authentication system using JWT (JSON Web Tokens).
- Implemented user registration, login, and session management functionalities.
- Built secure authentication middleware and password encryption mechanisms.
- Implemented User Profile Page with comprehensive user data management.
- Configured Docker containerization for application deployment.

#### Paritosh Tigga

- Built real-time chat feature using WebSocket technology for instant messaging.
- Designed and implemented chat server and client components for seamless communication.
- Handled WebSocket connections, message broadcasting, and user presence management.
- Utilized Socket.io for real-time bidirectional event-based communication.
- Integrated Redis for optimized chat performance and message caching.

#### Vinayak Anand

- Integrated the Stripe API to enable secure and reliable payment processing within the application.
- Implemented payment flows, including capturing user payment information, handling transactions, and managing subscriptions.
- Designed and developed the gamer dashboard on the frontend to provide a user-friendly interface for managing gaming activities.
- Created intuitive UI components and layouts to display relevant information and statistics for gamers.
- Implemented features such as game progress tracking, leaderboards, and user profiles within the gamer dashboard.
- Utilized React.js for building the frontend application, ensuring a clean and organized code structure.
- Implemented Tournament Pages.
- Assisted in CI/CD setup and Docker configuration for deployment.
- Developed unit tests to ensure application reliability.

#### Piyush Singh

- Designed and developed an engaging and main landing page to attract and onboard users.
- Created visually appealing UI components and layouts using React.js and Tailwind CSS.
- Implemented responsive design techniques to ensure optimal viewing experience across different devices.
- Utilized Redis as an in-memory data store to handle chat message storage and retrieval efficiently.
- Designed PPT & Video for evaluation.
- Implemented Landing Pages.
- Set up Swagger API documentation for better developer experience.

#### Sushant Kuril

- Implemented video chat feature using WebRTC (Web Real-Time Communication) technology.
- Developed WebRTC APIs for peer-to-peer video and audio communication channels.
- Built signaling server infrastructure using Socket.io for connection management.
- Implemented caching mechanisms using Redis to improve application performance and reduce database load.

#### Mahesh Datta

- Developed staff management system with role-based access control (RBAC).
- Implemented RESTful API endpoints for staff CRUD operations with pagination.
- Built staff dashboard with real-time monitoring and administrative controls.
- Created staff onboarding workflows with authentication and profile management.
- Implemented database optimization strategies for improved performance.

#### Shrijeet Kumar

- Developed tournament management system with dual-panel interfaces for users and admins.
- Implemented tournament lifecycle management including registration and bracket generation.
- Built tournament dashboard with real-time leaderboards and match tracking using React.js.
- Created tournament administration panel with participant management and result validation.

## How to run

### Option 1: Using Docker (Recommended)

Make sure you have Docker installed on your desktop, then simply run:

```
docker-compose up
```

### Option 2: Manual Setup

For development or if you prefer to run without Docker:

1. First, navigate to the frontend directory and install dependencies:

```
cd Apps/frontend
npm i
```

2. Then, navigate to the backend directory and install dependencies:

```
cd ../Backend
npm i
```

3. Move back to the root directory to start the application:

```
cd ../../
docker-compose up
```

## Contributors

- [Suvan Sarkar](https://github.com/suvansarkar) - S20220010220
- [Chaitanya Sikakolu](https://github.com/sikakoluchaitanya) - S20220010044
- [Vinayak Anand](https://github.com/vinayak-anand) - S20220010243
- [Piyush Singh](https://github.com/piyush-bug) - S20220010204
- [Paritosh Tigga](https://github.com/Overwatch10x) - S20220010164
- [Mahesh Datta](https://github.com/Mahesh-git888) - S20220020258
- [Sushant Kuril](https://github.com/SushantKuril) - S20220010219
- [Shrijeet Kumar](https://github.com/Shrijeet14) - S20220020312
