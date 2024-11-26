# Dog Shelter Application 🐶

## Overview
The **Dog Shelter** project is a C++ application developed to manage pet adoptions in a shelter using a layered architecture and dynamic memory management techniques. It provides a user-friendly interface for managing dog records, adoption data, and user interactions.

Key Features:
- **Administrator and User Modes**: Allows CRUD operations for dog records, including input validation and error handling.
- **Data Management**: Utilizes Standard Template Library (STL) vectors for in-memory data storage and implements file handling for persistent data (CSV/HTML formats).
- **Robust Exception Handling**: Custom exceptions are implemented to handle errors effectively, ensuring the program runs smoothly.
- **Graphical User Interface (GUI)**: Built with Qt, providing a clean and intuitive interface for users to interact with the shelter's records.
- **Undo/Redo Functionality**: Advanced functionality for managing dog records, allowing users to undo or redo actions.
- **Data Visualization**: Graphical displays of adoption statistics using Qt libraries, providing visual insights into shelter activity.

## Features in Detail

### 1. **Administrator and User Modes**
   - Administrator mode enables full CRUD operations on dog records.
   - Users can interact with the shelter's database to adopt pets, view available dogs, and manage records.

### 2. **Data Management**
   - The application stores dog records using STL vectors in C++ for efficient data handling.
   - Persistent data storage across sessions is supported through file handling, saving records in CSV/HTML formats.

### 3. **Exception Handling**
   - The program ensures reliability by using custom exception classes to handle various errors, such as invalid inputs and file handling errors.

### 4. **Graphical User Interface (GUI)**
   - An intuitive and user-friendly GUI was developed with **Qt**.
   - All functionalities are accessible via buttons and fields that allow easy navigation for both administrators and users.

### 5. **Undo/Redo Functionality**
   - The application includes a feature that tracks changes and allows users to undo or redo their actions (such as adding, removing, or editing dog records).

### 6. **Data Visualization**
   - The program presents adoption statistics using graphical charts to help administrators track adoption trends and shelter activities.

### 7. **Test Coverage**
   - Over 98% test coverage has been achieved for all core features, ensuring high reliability and maintainability.

## Technologies Used:
- **C++** for core logic and memory management
- **Qt** for GUI development
- **STL (Standard Template Library)** for data management
- **File Handling (CSV/HTML)** for data persistence
- **Custom Exception Handling** for error management

## Getting Started:
1. **Clone the Repository**:
`git clone https://github.com/Andreea410/Dog-Shelter`
2. **Build and Run the Application**:
- Open the project in **Visual Studio**.
- Compile and run the application.

3. **Navigate the GUI**:
- Log in as an administrator to perform CRUD operations.
- Switch to user mode to browse available dogs and adopt pets.

## Contributing:
Feel free to contribute to this project by opening issues or submitting pull requests with bug fixes, features, or improvements. Contributions are always welcome!

---

📧 **Contact**: andreeaungur494@yahoo.com  
🔗 **GitHub**: [Andreea410](https://github.com/Andreea410)
