# Vidiwise

**A Multimodal Deep Learning Platform for Smart Video Analysis and Graph-Based Querying**

Vidiwise is a powerful web application that extracts insights from videos using transcription, summarization, and knowledge graph generation. It leverages advanced deep learning models and Gemini API integration to analyze video content intelligently.

---

## 🔧 Project Setup Guide

### 🛠 Backend Setup (Terminal 1)

1. **Navigate to the backend folder:**

   ```bash
   cd backend
Create a virtual environment:

bash
Copy
Edit
python -m venv venv
Activate the virtual environment:

On Windows:

bash
Copy
Edit
venv\Scripts\activate
On macOS/Linux:

bash
Copy
Edit
source venv/bin/activate
Install all required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
Install OpenAI Whisper from GitHub:

bash
Copy
Edit
pip install git+https://github.com/openai/whisper.git
Add your Gemini API key:

Open main.py inside backend/app and insert your Gemini API key at line 25.

Add the same key in the .env file in the root vidiwise directory.

You can generate the API key via Google AI Studio.

Run the backend server:

bash
Copy
Edit
python app/main.py
💻 Frontend Setup (Terminal 2)
Navigate to the frontend folder:

bash
Copy
Edit
cd frontend
Install frontend dependencies:

bash
Copy
Edit
npm install
Start the frontend development server:

bash
Copy
Edit
npm start
🔍 Test the App
Use the YouTube Shorts links below to test how Vidiwise processes and summarizes video content:

- [Sample Video 1](https://www.youtube.com/shorts/v0NdBk67zaQ)
- [Sample Video 2](https://www.youtube.com/shorts/Tm3KCr10i4s)

⚠️ Notes
Keep both frontend and backend running simultaneously.

If you run into issues:

Double-check dependencies.

Ensure your API key is correctly set in both the .env file and main.py.

Verify internet access for API communication.

📦 Tech Stack
Frontend: React.js, HTML, CSS, JavaScript

Backend: Python, FastAPI

Libraries: Whisper (OpenAI), Gemini API, dotenv, requests, OpenCV

Deployment: Local (development/testing)

yaml
Copy
Edit


