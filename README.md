# Rise and Shine Task Management Application

## Overview

This repository contains the code for a task management application developed for the client Rise and Shine. The application is built using Flutter for the front-end, Node.js with Express for the backend, and MongoDB for the database. Firebase is utilized for chat functionality and notifications, and JWT tokens are implemented for authentication.

## Tech Stack

- **Frontend**: Flutter
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Chat**: Firebase
- **Notifications**: Firebase Cloud Messaging (FCM)
- **Authentication**: JWT tokens
- **Local Storage**: Shared Preferences (Flutter)

## Architecture Diagram
![image](https://github.com/dhruv2x/TaskHive/assets/84621641/2cc6e467-abf1-4eb7-9932-824435575d9c)


## Modules and Features

### Task & Project Management
This module allows users to create, assign, and track tasks and projects. Features include:
- **Task Attributes**: Name, assignee, checker, priority level
- **Workflow Management**: Organize and track the progress of tasks and projects

### Mindmap
A brainstorming and strategic planning tool with features such as:
- **Graph-type Charts**: Visualize ideas with nodes and edges
- **Text Embedding**: Add detailed descriptions within nodes

### Taskboard
A personal task management feature with:
- **Tasks and Subtasks**: Create detailed task hierarchies
- **Auto Reminders**: Notifications to ensure deadlines are met

### Whiteboard
A collaborative space for team brainstorming sessions:
- **Sticky Notes**: Add and share notes dynamically
- **Team Collaboration**: Share whiteboards with team members

### Calendar
Integrates with Task & Project Management and Taskboard modules to display tasks in a monthly view:
- **Time Management**: View deadlines and appointments
- **Scheduling**: Plan and organize tasks effectively

### Chat
A real-time communication tool for direct messaging and group chats:
- **Direct Messaging**: One-on-one communication
- **Group Chats**: Team and project-based communication

## Additional Features

### Notifications
- **Real-time Updates**: Keep users informed about task, project, and communication updates
- **FCM Integration**: Ensure all team members are aware of important changes and deadlines

### Login/Registration
- **Secure Authentication**: Access control to personalized workspaces using JWT tokens

### Profile Management
- **User Information**: Manage personal and professional information within the app

## Getting Started

### Prerequisites
- Flutter SDK
- Node.js and npm
- MongoDB
- Firebase account for chat and FCM

### Installation

1. **Clone the repository**
   ```bash
   git clone xyz
   cd rise-and-shine-task-manager
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Setup MongoDB**
   - Ensure MongoDB is running on your machine or set up a MongoDB Atlas account and configure the connection string.

4. **Setup Firebase**
   - Create a Firebase project and configure Firestore and FCM.
   - Download `google-services.json` and place it in the appropriate directory in your Flutter project.

5. **Run the backend server**
   ```bash
   npm start
   ```

6. **Install frontend dependencies**
   ```bash
   cd ../frontend
   flutter pub get
   ```

7. **Run the Flutter app**
   ```bash
   flutter run
   ```

## Contact

For any inquiries, please contact the development team at [chauhandhruv351@gmailcom](mailto:chauhandhruv351@gmail.com).

---
