# Capture The Flag (CTF) Management System

## Overview

The **Capture The Flag (CTF) Management System** is a Java-based application designed to manage and organize CTF events. It provides a platform for users to register, create CTFs, upload challenges, form teams, and track scores. The system is built using **Object-Oriented Programming (OOP)** principles and features a **Graphical User Interface (GUI)** for ease of use.

## Features

- **User Authentication**: Users can register and log in using their email and password.
- **CTF Management**: Organizers can create CTFs with a unique name and entry code.
- **Challenge Management**: Organizers can upload challenges with details like title, description, points, category, and flag.
- **Team Management**: Players can form teams and add members.
- **Scoreboard and Rankings**: The system maintains a scoreboard for each CTF and ranks teams based on their scores.

## Technologies Used

- **Java**: The project is implemented in Java, leveraging its OOP features like inheritance, encapsulation, and polymorphism.
- **Swing (GUI)**: The GUI is built using Java Swing, providing a user-friendly interface for navigation.
- **Serialization (File I/O)**: Data persistence is achieved using Java serialization, allowing objects to be saved to and loaded from files.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)**: Ensure you have JDK installed on your machine. You can download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html).
- **IDE**: You can use any Java IDE like IntelliJ IDEA, Eclipse, or NetBeans.

### Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/CTF-Management-System.git
   cd CTF-Management-System
   ```

2. **Open the Project in Your IDE**:
   - Import the project into your preferred IDE.
   - Ensure that the `MainRunner.java` class is set as the main class.

3. **Run the Project**:
   - Run the `MainRunner.java` class to start the application.
   - The application will launch with a welcome screen where you can register or log in.

## Project Structure

### Key Classes

- **AppController**: Manages navigation between panels and handles interactions between the GUI and backend.
- **User**: Represents a user in the system and handles authentication.
- **Player**: Extends `User` and manages player-specific details like solved challenges and CTF participations.
- **Team**: Represents a team and manages team members and their activities.
- **CTF**: Represents a CTF event and manages challenges, teams, and the scoreboard.
- **Challenge**: Represents a challenge in a CTF and handles file operations for challenge folders.
- **Scoreboard**: Manages team scores and rankings for a CTF.

### GUI Classes

- **WelcomePanel.java**: Displays the welcome screen with options to log in or register.
- **LoginPanel.java**: Handles user login functionality.
- **RegistrationPanel.java**: Handles user registration functionality.
- **CtfMenuPanel.java**: Displays the main menu for CTF-related actions (create, organize, play CTFs).
- **CtfRegisterPanel.java**: Allows users to organize and register a new CTF.
- **CtfChallengesPanel.java**: Allows organizers to upload challenges for a CTF.
- **CtfScoreboaredPanel.java**: Displays the scoreboard for a CTF.
- **TeamPanel.java**: Manages team-related actions (changing team name, adding/removing players).

### Backend Classes

- **User.java**: Handles authentication (login, registration, logout).
- **Player.java**: Manages player-specific details.
- **Team.java**: Manages team members and their activities.
- **CTF.java**: Manages challenges, teams, and the scoreboard.
- **Challenge.java**: Handles file operations for challenge folders.
- **Scoreboard.java**: Manages team scores and rankings.

## Future Enhancements

- **Database Integration**: Replace file-based storage with a database (e.g., MySQL) for better scalability and performance.
- **Advanced Security Features**: Implement password hashing and encryption for secure storage of user credentials.
- **Scalability**: Add support for larger CTF events with more participants and challenges.


## Conclusion

The **Capture The Flag (CTF) Management System** is a robust application that simplifies the organization and participation in CTF events. By leveraging Java's OOP features and Swing for the GUI, the project provides a seamless user experience. With future enhancements like database integration and advanced security features, the system can be further improved to meet the needs of larger and more complex CTF events.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
