# Jarvis-like Personal Assistant

## **Overview**
This project is a robust personal assistant inspired by Jarvis, designed to run on a personal computer. The assistant is equipped with advanced AI capabilities and can perform tasks such as opening browsers, playing music, searching the web, and interacting with the active display. It operates as a background service, listens for the wake word "Hey Jarvis," and executes commands in a super-responsive manner.

## **Features**
1. **Wake Word Activation**:
   - Listens for the wake word "Hey Jarvis" using a low-latency voice detection system.
2. **AI-Powered Command Parsing**:
   - Utilizes Groq API for advanced natural language understanding (NLU).
3. **UI Automation**:
   - Full control over mouse and keyboard for navigating the system and applications.
4. **Screen Content Interaction**:
   - Recognizes and interacts with on-screen elements dynamically using OCR.
5. **Specialized Task Support**:
   - Web searching, media playback, file management, and system-level commands.
6. **Background Service**:
   - Operates silently and efficiently in the background, ready for activation.
7. **Cross-Functional Interruption**:
   - Allows the user to interrupt the assistant's automation at any time.

---

## **Project Structure**

```
jarvis-assistant/
|-- src/
|   |-- voice_activation/
|   |   |-- wake_word_detector.py
|   |-- command_parsing/
|   |   |-- command_parser.py
|   |-- ui_automation/
|   |   |-- mouse_control.py
|   |   |-- screen_reader.py
|   |-- ai_integration/
|   |   |-- groq_integration.py
|   |-- tasks/
|       |-- browser_control.py
|       |-- media_control.py
|       |-- file_management.py
|-- docs/
|   |-- README.md
|   |-- INSTALLATION.md
|   |-- USAGE.md
|-- tests/
|-- requirements.txt
|-- main.py
|-- setup.py
```

### **Directories and Files**
- **src/**: Contains all source code.
  - `voice_activation/`: Handles wake word detection.
  - `command_parsing/`: Responsible for parsing and understanding user commands.
  - `ui_automation/`: Contains modules for interacting with the UI (mouse, keyboard, and screen).
  - `ai_integration/`: Integrates the Groq API for AI inference.
  - `tasks/`: Specialized task modules for browser, media, and file management.
- **docs/**: Contains documentation for installation, usage, and contributing.
- **tests/**: Contains unit and integration tests.
- **requirements.txt**: Lists all Python dependencies.
- **main.py**: Entry point for the assistant.
- **setup.py**: Script for packaging the project.

---

## **Installation**

### Prerequisites
- Python 3.8+
- A Groq API key
- Microphone for voice input

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/jarvis-assistant.git
   cd jarvis-assistant
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure the Groq API key:
   - Add your Groq API key to a `.env` file in the root directory:
     ```
     GROQ_API_KEY=your_api_key_here
     ```
4. Run the assistant:
   ```bash
   python main.py
   ```

---

## **Usage**
1. Start the program and say "Hey Jarvis" to activate the assistant.
2. Use voice commands such as:
   - "Open browser and search for Python tutorials."
   - "Play music."
   - "Show me my recent files."
   - "Adjust system volume."
3. To stop the assistant, use the keyboard shortcut `Ctrl+C` in the terminal.

---

## **Documentation**

### [Installation Guide](docs/INSTALLATION.md)
Step-by-step guide to set up the project on your machine.

### [Usage Guide](docs/USAGE.md)
Detailed explanation of commands, functionalities, and troubleshooting.

### [Contributing Guidelines](docs/CONTRIBUTING.md)
Instructions for contributing to the project.

---

## **Roadmap**

### **Phase 1: Core Framework and Setup**
- Establish project structure and integrate Groq API.
- Develop a logging system.

### **Phase 2: Wake Word Detection**
- Implement low-latency wake word detection.
- Optimize for resource efficiency.

### **Phase 3: Command Parsing**
- Enable AI-powered intent recognition using Groq.
- Add fallback for ambiguous commands.

### **Phase 4: UI Automation**
- Build modules for cursor and keyboard control.
- Implement OCR-based screen interaction.

### **Phase 5: Specialized Features**
- Add modules for browser control, media playback, and file management.

### **Phase 6: Background Service**
- Run the assistant as a Windows background process.

### **Phase 7: Packaging and Deployment**
- Use `PyInstaller` to generate an executable `.exe` file.

---

## **Contributing**
Contributions are welcome! Please read the [CONTRIBUTING.md](docs/CONTRIBUTING.md) for details on the code of conduct and submission process.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Contact**
For support or inquiries:
- **Email**: your-email@example.com
- **GitHub Issues**: [Issue Tracker](https://github.com/your-username/jarvis-assistant/issues)

---

