

A code editor code editor where users can seamlessly code together.


## 🔮 Features

- Real-time collaboration on code editing across multiple files
- Create, open, edit, save, delete, and organize files and folders
- Option to download the entire codebase as a zip file
- Unique room generation with room ID for collaboration
- Comprehensive language support for versatile programming
- Syntax highlighting for various file types with auto-language detection
- Code Execution: Users can execute the code directly within the collaboration environment
- Instant updates and synchronization of code changes across all files and folders
- Notifications for user join and leave events
- User presence list with online/offline status indicators
- Real-time group chatting functionality
- Real-time tooltip displaying users currently editing
- Auto suggestion based on programming language
- Option to change font size and font family
- Multiple themes for personalized coding experience
- Collaborative Drawing: Enable users to draw and sketch collaboratively in real-time
- Copilot: An AI-powered assistant that generates code, allowing you to insert, copy, or replace content seamlessly within your files.

## 🚀 Live Preview

You can view the live preview of the project [here]().

## ⚙️ Installation

### Method 1: Manual Installation

1. **Fork this repository:** Click the Fork button located in the top-right corner of this page.
2. **Clone the repository:**
   ```bash
   git clone https://github.com/Rohit8940/CodeSangam.git
   ```
3. **Create .env file:**
   Inside the client and server directories create `.env` and set:

   Frontend:

   ```bash
   VITE_BACKEND_URL=<your_server_url>
   ```

   Backend:

   ```bash
   PORT=3000
   ```

4. **Install dependencies:**
   ```bash
   npm install     # Run in both client and server directories
   ```
5. **Start the servers:**
   Frontend:
   ```bash
   cd client
   npm run dev
   ```
   Backend:
   ```bash
   cd server
   npm run dev
   ```
6. **Access the application:**
   ```bash
   http://localhost:5173/
   ```