# Online Code Compiler (With Real-time code collaboration)

This project is an Online Code Compiler that supports multiple programming languages, including C, C++, Java, and Python. It allows users to write, compile, and execute code directly in the browser. Additionally, it includes a chat feature for real-time communication among users and displays active users. One of the standout features is real-time code collaboration, enabling multiple users to work on the same code simultaneously.

## Features
- Real-time code collaboration
- Multi-language code compilation and execution (C, C++, Java, Python)
- Real-time chat functionality
- Display of active users
- Responsive design for use on desktops, tablets, and mobile devices

## Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/dipesh6264/online-code-compiler.git
    ```
2. Navigate to the project directory:
    ```sh
    cd online-code-compiler
    ```
3. Install the required dependencies (example using Node.js and npm):
    ```sh
    npm install
    ```
4. Start the server:
    ```sh
    node app.js
    ```

## Modules
- **Collaboration Module:** Facilitates real-time code collaboration among users
- **Compiler Module:** Handles code compilation and execution using a server-side API.
- **Chat Module:** Enables real-time chat functionality using WebSockets.
- **User Module:** Manages active users and their interactions.


## Demonstration
![image](https://github.com/dipesh6264/online-code-compiler/assets/134261406/27d2fa0d-699e-4eac-8b02-89818617c0a5)

The following steps demonstrate how to use the Online Code Compiler:
1. Select the programming language from the dropdown menu.
2. Enter your code in the provided textarea.
3. Optionally, provide input values for your code execution.
4. Click the "Run Code" button to compile and execute your code.
5. The output will be displayed in the "Output" section.
6. To use the chat feature, type your message in the chat input box and click "Send".
7. Active users are displayed in the "Active Users" section.
8. For real-time collaboration, share the link with other users, and they can join to edit the code simultaneously.
