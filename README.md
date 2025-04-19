# Code Pulse - Real-Time Collaborative Coding Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


Code Pulse is a real-time collaborative coding platform that allows developers to code together, communicate via video calls, and execute code in multiple programming languages.

---

## ✨ Features

- **Real-time code collaboration** - Multiple users can edit code simultaneously.
- **Video calling** - Built-in WebRTC video conferencing for team collaboration.
- **Multi-language support** - Supports JavaScript, Python, Java, C++, Go, Rust, and more.
- **Code execution** - Run your code and see output in real-time.
- **Syntax highlighting** - Language-specific syntax highlighting for better readability.
- **Secure rooms** - Private rooms with unique IDs for collaboration.

---

## 🚀 Getting Started

### Prerequisites

Before you start, ensure you have the following software installed on your machine:

- **Node.js**: Download from [Node.js Official Website](https://nodejs.org/).
- **npm**: Installed automatically with Node.js.

---

### Installation

To install and set up the project, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Dhirajsharma2060/real-time-debugger
   ```

2. **Navigate to the project directory**:

   ```bash
   cd real-time-debugger
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

4. **Start the development server**:

   ```bash
   npm run dev
   ```

   This will run the frontend code.

5. **Start the backend server**:

   ```bash
   npm run server:dev
   ```
## 🏗️ Project Structure

```bash
.env
.gitignore
package.json
README.md
server.js
public/
    code.png
    codepulse.png
    favicon.ico
    index.html
    logo192.png
    logo512.png
    manifest.json
    robots.txt
src/
    Action.js
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
    reportWebVitals.js
    setupTests.js
    socket.js
    componenets/
        Client.js
        Editor.js
        ResizablePane.css
        ResizablePane.js
        VideoCall.js
    pages/
        EditorPage.js
        Home.js
```
##  📄 Available Scripts

In the project directory, you can run:

```bash
npm run dev
```
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

```bash
npm run build
```
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.
- **npm run server:dev**:Starts the backend server in development mode using nodemon.
- **npm run server:prod**:Starts the backend server in production mode.


## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. **Fork the repository.**
2. **Create your feature branch (git checkout -b feature/amazing-feature).**
3. **Commit your changes (git commit -m 'Add some amazing feature').**
4. **Push to the branch (git push origin feature/amazing-feature).**
5. **Open a Pull Request.**


## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements
- [CodeMirror](https://codemirror.net/) - Text editor implementation.
- [Socket.io](https://socket.io/) - Real-time communication.
- [Judge0](https://github.com/judge0/judge0) - Code execution API.
- [WebRTC](https://webrtc.org/) - Video calling capabilities.
## 📞 Contact
- **GitHub:** CodePulse
<p align="center"> Made with 💛 by the Code Pulse team </p>





