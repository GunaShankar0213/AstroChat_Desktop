# AstroChat Desktop - Cross-Platform Chat and AI Assistant

AstroChat Desktop is a feature-rich application that integrates a real-time chat system, AI voice assistant, and several advanced functionalities. It is built using **Python**, **Tkinter** for the user interface, and **Firebase** for real-time chat synchronization with the mobile version. The desktop app also provides real-time updates through a **News API**, **Wikipedia API**, and **YouTube search** using both voice and text inputs. It is designed to function cross-platform with features like threaded processes to prevent crashes and local caching for optimized performance.

## Features

### 1. **AI Voice Assistant**
   - **Voice Command Integration**: The AI assistant can capture keywords from speech and convert them to text using **speech-to-text** technology.
   - **Threading for Stability**: To prevent unwanted crashes, threading is used for voice command processing, ensuring smooth operation even when handling multiple tasks simultaneously.
   - **Real-time Voice-to-Text**: Users can use voice commands for searching YouTube, getting Wikipedia information, and navigating through the app.

### 2. **Real-time Chat with Firebase**
   - The desktop version is fully integrated with the **AstroChat Android app** via **Firebase**, allowing seamless real-time communication between the platforms.
   - **Group Chat Room**: The desktop app also supports group chats through a **TCP/IP protocol**, with messages exchanged in real-time between users in a local network. These messages are not stored in Firebase to maintain privacy.

### 3. **Dashboard with Latest Trends**
   - The app includes a **dashboard** that displays the latest trends, such as top news stories and updates, powered by the **News API**. 
   - This dashboard updates in real-time, providing users with the latest information at their fingertips.

### 4. **Local Authentication and Caching**
   - **Authentication**: User authentication is handled using **local cache** and **SQL** for secure and fast login processes without always relying on external services.
   - **Local Data Storage**: Caching is used to store frequently accessed data locally, ensuring a faster and more efficient user experience.

### 5. **Cross-Platform Support**
   - The app is designed to run across multiple platforms, ensuring that users on different operating systems (Windows, macOS, Linux) can interact with the app without issues.
   
### 6. **Search and Query Features**
   - **YouTube Search**: Users can search YouTube videos using either voice commands or text input directly within the app.
   - **Wikipedia Queries**: The voice assistant can also fetch information from Wikipedia, enabling users to ask questions or get data on various topics, all through voice or text.

### 7. **UI and Navigation**
   - The **UI** is built using **Tkinter**, providing a clean, intuitive design for interacting with the application. 
   - Users can navigate between pages and perform actions using voice commands, making the app more interactive and accessible.

## How It Works

1. **Voice Assistant Activation**: 
   - The voice assistant listens for commands and processes speech-to-text to execute various functions such as searching YouTube or Wikipedia.
   
2. **Real-time Communication**: 
   - Messages sent from the Android app are immediately synchronized with the desktop app via Firebase.
   - Group chats use **TCP/IP protocol** for communication, which is not stored in Firebase but rather managed locally within the network.

3. **News and Trends**: 
   - The latest news trends are pulled in real-time via the **News API** and displayed on the dashboard.
   
4. **Search Capabilities**: 
   - Voice and text inputs trigger search queries on YouTube and Wikipedia, returning relevant results to the user.

## Technologies Used
- **Python**: For building the core logic and handling real-time updates.
- **Tkinter**: For creating the graphical user interface (GUI).
- **Firebase**: For real-time synchronization of messages between the mobile and desktop apps.
- **News API**: To fetch and display the latest news trends.
- **Speech-to-Text**: For converting voice commands into text.
- **TCP/IP Protocol**: For handling real-time group chat communications that are not stored in Firebase.
- **SQL & Local Cache**: For managing user authentication and storing cached data.

## Demo and Usage
You can verify the functionality through the code sample available at [AstroChat Desktop Complete Code](https://github.com/GunaShankar0213/AstroChat_Desktop/blob/main/Astro%20chat%20complte%20code.txt).


This project demonstrates the integration of multiple technologies to create a versatile and interactive cross-platform chat and AI assistant application. It combines real-time messaging, voice recognition, and seamless communication with a sleek user interface.

---

Feel free to check out the code in the repository and contribute to the project!
