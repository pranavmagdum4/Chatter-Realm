# Chatter Realm - Real-Time Chat Application

Chatter Realm is a feature-rich web chat application that closely resembles the WhatsApp Web version. Built using a diverse tech stack, this project provides essential functionalities such as one-to-one messaging, group messaging, offline messaging, and user authentication with JWT.

## Key Features

### Basic Functionality with One Server
- Established WebSocket connection to enable real-time messaging
- Implemented one-to-one messaging functionality

### Basic Functionality with Multiple Backend Servers
- Utilized Redis to map users to servers (alternatively, Kafka could be used)

### Group Messaging
- Enabled group messaging functionality

### Offline Messaging
- Implemented offline messaging capabilities

### Login and Authentication
- Implemented user authentication using JWT
- Integrated login and signup functionality

### Containerization
- Containerized the application using Docker
- Utilized Docker Compose to manage and orchestrate the containers

## Tech Stack

### Frontend
- Next.js
- Socket.IO
- Tailwind CSS
- React Hooks (useState, useEffect)

### Backend
- Express.js
- Socket.IO
- JWT
- MongoDB

### Database
- MongoDB

### Caching
- Redis

### Containerization
- Docker
- Docker Compose


## Future Enhancements
- Implement end-to-end encryption for secure messaging
- Integrate file sharing and media support
- Develop a mobile app version of the chat application
- Enhance the user interface and user experience

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

