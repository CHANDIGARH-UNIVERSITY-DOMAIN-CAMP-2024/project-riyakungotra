
## Overview
The Smart Disaster Management System is a mobile application designed to enhance disaster management processes. By leveraging real-time data, APIs, and cloud services, this app aims to provide timely information and emergency support during disaster situations.

## Features
- **Disaster Information**: Displays up-to-date disaster-related details.
- **Emergency Contacts**: Quick access to essential emergency contact numbers.
- **Real-Time Alerts**: Integrates with APIs and Firebase to deliver notifications.
- **Local Database Support**: Utilizes SQLite for offline functionality.
- **User-Friendly Interface**: Easy navigation through screens like home, disaster info, and emergency contacts.


## Technology Stack
- **Programming Language**: Dart (Flutter framework)
- **Backend Integration**:
  - APIs for disaster information.
  - Firebase for notifications and cloud storage.
- **Local Database**: SQLite
- **Dependency Management**: Defined in `pubspec.yaml`

## Directory Structure

### **src**
- **Core Files**:
  - `main.dart`: Entry point of the Flutter application.
  - `home_screen.dart`: Main interface for user interaction.
  - `disaster_info_screen.dart`: Displays disaster details.
  - `emergency_contacts_screen.dart`: Lists and manages emergency contacts.
- **Services**:
  - `api_service.dart`: Handles API requests and responses.
  - `firebase_service.dart`: Manages Firebase operations.
  - `sqlite_service.dart`: Provides SQLite database management.
- **Configuration**:
  - `pubspec.yaml`: Lists dependencies and project metadata.
  - `project str.ini`: Project structure or configuration file.

### **modules**
- **Localization**:
  - `Lang001.dart`: Handles language-specific operations.


## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/smart-disaster-management.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd smart-disaster-management
   ```
3. **Install dependencies**:
   ```bash
   flutter pub get
   ```
4. **Run the application**:
   ```bash
   flutter run
   ```




