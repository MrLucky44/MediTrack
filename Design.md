# System & UI Design Document

## 1. Overall System Architecture

The MediTrack application follows a client-server model where the frontend communicates with the backend API over HTTPS. The frontend is built using React Native, and the backend uses Django REST Framework. Notifications are handled via Firebase Cloud Messaging.

## 2. User Interface Design

The interface is designed to be minimal, accessible, and optimized for mobile users. Wireframes were created using Figma and translated into live components with React Native.

### Pages:

- **Login / Register** – User authentication  
- **Dashboard** – Overview of today’s medication and actions  
- **Medication Editor** – Add/edit medication entries  
- **Reminder Setup** – Schedule doses by time and frequency  
- **History Viewer** – View previously taken or missed doses

## 3. Color Scheme & Fonts

- Primary color: `#58C0A9` (calming green)
- Accent color: `#FFFFFF`
- Typography: Inter (light, regular, bold)

## 4. Navigation

Implemented using React Navigation with stack and tab-based routing.

## 5. Responsiveness

UI tested on:
- iPhone 13 / iOS Simulator
- Android Pixel 4 Emulator
- Real Android device (Samsung Galaxy A51)
