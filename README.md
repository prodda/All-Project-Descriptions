# 💻 Pradham Rodda's Computer Science Projects

Welcome to my portfolio of computer science projects! This repository contains work I’ve completed in different languages, each demonstrating core concepts in software development, systems programming, and embedded systems. 

---

## 📂 Java Projects

### Basic Linked List
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Blackjack
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O
  
### Cell Game
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Graph Maze
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Hash Set
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Heavy Bag
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Minimum Snippet
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Polymorphic Tree
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O
  
## 📊 C Projects

### Calendar
**Description**:  
A calendar application implemented in C that uses an array of linked lists to store and manage scheduled events across multiple days, with support for dynamic memory allocation and customizable sorting.

**Key Concepts**:  
- Dynamic Memory Allocation
- Function Pointers
- Linked Lists

### Document Manager
**Description**:  
A structured document editing system that supports adding paragraphs and lines, replacing and removing text, and highlighting specific content within a document. It models real-world document processing using static memory.

**Key Concepts**:  
- Struct-Based Data Modeling
- String Replacement and Parsing
- Static Memory Management

### Draw Figures
**Description**:  
A console-based program that interacts with the user to draw rectangles and triangles based on given dimensions and seed values. It uses formatted input/output to handle requests and error states.

**Key Concepts**:  
- Procedural Programming with Functions
- Input Validation and Control Flow
- Character-Based Console Output

### Grades Calculator
**Description**:  
Processes assignment grades, applies penalties for late submissions, drops the lowest scoring assignments, and computes the final numeric grade with optional statistics like mean and standard deviation.

**Key Concepts**:  
- Array Manipulation
- Modular Function Design
- Input Parsing and State Management

### Photo Album
**Description**:  
Implements a virtual photo album that dynamically stores photos and their descriptions, allowing users to print, add, and delete entries while managing memory allocation properly.

**Key Concepts**:  
- Dynamic Memory Management
- Pointer Safety and NULL Checking
- Structured Abstraction via Functions

### Shell Junior
**Description**:  
A basic shell interpreter that supports command execution using system calls like fork and execvp, along with built-in commands like cd and exit.

**Key Concepts**:  
- Process Creation with fork
- Command Execution using execvp
- Input Tokenization and Argument Handling

### Shell
**Description**:  
An advanced shell supporting logical operations, file redirection, piping, and subshell execution. The shell parses commands into a tree and recursively executes them.

**Key Concepts**:  
- Recursive Tree-Based Command Execution
- File Descriptor Redirection and Duplication
- Inter-Process Communication via Pipes

### Text Manipulation
**Description**:  
A string-processing utility in C that removes leading/trailing spaces and centers strings using pointers and manual memory control.

**Key Concepts**:  
- Pointer Arithmetic
- Manual String Buffer Manipulation
- Defensive Programming with Input Validation

### Threads
**Description**:  
A multithreaded C program that performs either a parallel sum or maximum search on an array of integers, utilizing pthreads and mutexes to ensure thread safety and performance measurement.

**Key Concepts**:  
- POSIX Threading (pthread_create, pthread_join)
- Mutex-Based Synchronization
- Parallel Array Partitioning

### User Interface
**Description**:  
A command-line interface for interacting with a structured document editor. The interface parses user commands, routes them to appropriate handlers, and maintains a persistent document state.

**Key Concepts**:  
- Command Parsing and Dispatching
- State Management via Struct Interaction
- Input Sanitization and Validation
  
## 🧠 AVR Assembly Projects

### Assembly Basics
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Fibonacci
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O

### Isqrt
**Description**:  

**Key Concepts**:  
- Object-Oriented Programming  
- Exception Handling  
- File I/O
  
## 🔌 Euchre Game
**Description**:  
This project implements the classic trick-taking card game Euchre in Python, supporting both human and AI players. The program structures the game into distinct components, including player strategies, card objects, game flow logic, trick resolution, and scoring. The AI players use simple decision heuristics to play cards based on their hands and the current trump suit. The game enforces all Euchre-specific rules, such as team play, trump suit logic, left and right bowers, and trick-taking rules. Additionally, the program includes error handling for illegal moves, string-to-object conversions, and complex round logic.

**Key Concepts**:  
- Object-Oriented Design Patterns: Extensive use of class hierarchies for players, cards, and game state to support modular design, encapsulation, and reuse (e.g., Player, SimplePlayer, Card, Pack, Game).
- Custom Rule Enforcement and State Transitions: Implementation of non-trivial game rules such as trump mechanics, trick evaluation, and scoring logic using clean control structures and class methods.
- Strategy Pattern with Polymorphism: Different player behaviors (human vs. AI) are abstracted using polymorphic classes, making it easy to test or swap in new player strategies.
- State Machine Logic: The game engine uses discrete, ordered phases (deal, bidding, playing, scoring) to manage turn-based progression and enforce valid state transitions.
- 

## ⚡ Terpiez App
**Description**:  
This project is a full-stack Flutter-based augmented reality (AR) game app named Terpiez, where users explore real-world locations to capture creatures. The app includes features like map integration, background location tracking, Redis-based remote data synchronization, local and push notifications, sensor interaction (e.g., accelerometer), and persistent creature data storage. The design also supports gamified elements like stats tracking and personalized creature logs. The app supports background services and secure storage, making it suitable for always-on mobile gaming.

**Key Concepts**:  
- Flutter UI & State Management: Use of widgets, Provider, and global state keys to manage complex UI updates and user interactions across multiple screens (e.g., maps, stats, capture).
- Asynchronous Background Services & Location Tracking: Integration with flutter_background_service, Geolocator, and Redis for continuous data syncing and geo-based triggers even when the app is not in the foreground.
- Secure Persistent Storage & Notifications: Secure data handling using flutter_secure_storage and real-time alerts via flutter_local_notifications, allowing personalized and time-sensitive gameplay experiences.
- Redis Database Communication: Asynchronous read/write operations to Redis allow fast syncing of player data and creature states across devices.
- Custom UI/UX with Flutter Animations: Animated creature cards, transitions, and themed map interactions enhance engagement and provide visual feedback.

## 🔧 ShareBear App
**Description**:  
Share Bear is a collaborative Flutter application designed to facilitate peer-to-peer task management, idea sharing, and team collaboration through a streamlined mobile interface. It enables users to create, edit, and post “shares” — task cards or updates — that include titles, tags, and descriptions. Each share is stored in Firestore, enabling real-time updates across all devices. The app supports dynamic user interfaces, tag-based filtering, and asynchronous database operations. It also includes UI components like sliding pages, reusable widgets, and an interactive app bar to ensure a clean, engaging user experience. The focus of the app is creating a supportive and interactive digital community where users can contribute ideas, view others’ contributions, and engage in shared productivity goals — all in real-time.

**Key Concepts**:  
- Cloud Firestore Integration for Real-Time Collaboration: The app connects to Firebase's Firestore database to store and retrieve shared items. It supports real-time updates, asynchronous reads/writes, and seamless integration between front-end UI and cloud storage.
- Component-Based UI Design in Flutter: The UI is structured around reusable Flutter widgets, making it easy to display posts (shares), create dynamic forms, and maintain separation of concerns between layout and logic. Screens are modularized for different use cases like posting, browsing, and onboarding.
- Asynchronous State Management & Navigation Flow: Implements Dart’s async/await patterns to handle Firestore operations and user interactions smoothly. The app features robust routing between onboarding, home, and sharing screens, ensuring a fluid multi-page navigation experience.


## 📬 Contact
Feel free to reach out if you have questions or want to see the actual project repositories:

📧 Email: pradham726@gmail.com
💼 LinkedIn: linkedin.com/in/pradham-rodda

🚧 More projects coming soon as I continue to explore and grow in the field of computer science!
