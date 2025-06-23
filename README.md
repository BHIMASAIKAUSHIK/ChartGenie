# ChartGenie 📊🎤

An AI-powered dashboard creator that transforms CSV data into dynamic visualizations through text prompts or voice commands.

## ✨ Features

- **Multi-Modal Input**: Accept prompts via text input or voice commands using ElevenLabs Text-to-Speech API
- **CSV File Upload**: Simple drag-and-drop CSV file processing
- **AI-Powered Analysis**: Dual AI processing pipeline with Gemini API and Llama 4 for intelligent data interpretation
- **Dynamic Visualizations**: Real-time chart generation using React and Chart.js
- **Conversation Memory**: PostgreSQL database stores previous interactions for context-aware responses
- **Re-rendering Capability**: Update visualizations based on follow-up prompts without re-uploading data

## 🏗️ Architecture

Built using **MVC (Model-View-Controller)** design pattern for clean separation of concerns:

- **Model**: PostgreSQL database for data persistence and conversation history
- **View**: React frontend with Chart.js for dynamic visualizations
- **Controller**: RESTful API endpoints handling data processing and AI integration

## 🔧 Tech Stack

### Frontend
- React.js
- Chart.js
- HTML/CSS/JavaScript

### Backend
- Node.js/Express (assumed)
- RESTful API design
- Docker containerization
- PostgreSQL database

### AI Integration
- **Gemini API**: Final output processing and JSON formatting
- **Llama 4**: Input refinement and data analysis
- **ElevenLabs API**: Text-to-speech functionality

## 🚀 How It Works

1. **Data Input**: Upload CSV file through the web interface
2. **Prompt Entry**: Enter analysis request via text field or voice command
3. **AI Processing**: 
   - Llama 4 processes and refines user input
   - Gemini API generates structured JSON output
4. **Visualization**: React + Chart.js renders dynamic charts based on JSON data
5. **Iteration**: Users can refine visualizations through additional prompts
6. **Memory**: PostgreSQL stores conversation context for intelligent follow-ups

## 📈 Use Cases

- Quick data exploration and analysis
- Accessible data visualization for non-technical users
- Voice-driven analytics for hands-free operation
- Iterative chart refinement through natural language

## 🎯 Project Highlights

- Seamless integration of multiple AI APIs in a processing pipeline
- Multi-modal user interface supporting both text and voice input
- Real-time data visualization with dynamic re-rendering
- Persistent conversation memory for enhanced user experience
- Full-stack implementation with modern web technologies

## 🏆 Hackathon Project

This project was developed during a hackathon, showcasing rapid prototyping skills and innovative use of AI technologies for data visualization.

---

*ChartGenie - Where data meets conversation* 🚀
