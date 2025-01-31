# Comprehensive Project Suite: AI-Powered Tools and Applications

This repository contains a collection of modern, AI-powered applications and tools designed to enhance productivity, learning, and collaboration. Below is a detailed overview of each project, its features, and how to set it up.

---

## *1. Face Recognition Attendance System*

A web-based attendance system that uses face recognition technology to track attendance in real-time.

### *Features*
- Real-time face recognition
- Attendance tracking and management
- Analytics dashboard with trends and statistics
- Late arrival tracking
- Attendance history and logs
- Export attendance data (CSV, Excel, PDF)
- Clear attendance records (individual dates or all)
- Modern, responsive UI

### *Tech Stack*
- *Backend*: Flask (Python)
- *Frontend*: Next.js (React)
- *Libraries*: OpenCV, dlib, face-recognition, pandas, xlsxwriter, reportlab

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd face_recognition_attendance
   
2. Set up Python virtual environment:
   bash
   python -m venv venv
   .\venv\Scripts\activate
   pip install -r requirements.txt
   
3. Set up frontend:
   bash
   cd frontend
   npm install
   
4. Run the application:
   - Backend: python app.py
   - Frontend: npm run dev

---

## *2. MoodVideo: Facial Expression-Driven 3D Model Interaction*

An interactive application that uses facial detection to overlay 3D models in real-time.

### *Features*
- Real-time face detection using TensorFlow and MediaPipe
- 3D model integration with React Three Fiber and Drei
- Interactive animations powered by GSAP and Framer Motion
- Seamless integration with Spline for 3D rendering
- Responsive design using Tailwind CSS

### *Tech Stack*
- *Frontend*: Next.js, React, Tailwind CSS
- *3D Modeling*: Three.js, React Three Fiber, Spline
- *Face Detection*: TensorFlow, MediaPipe
- *Animations*: GSAP, Framer Motion

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd moodvideo-new
   
2. Install dependencies:
   bash
   npm install
   
3. Run the development server:
   bash
   npm run dev
   

---

## *3. E-Learning Dashboard*

A modern dashboard for managing and visualizing e-learning data.

### *Features*
- Real-time data visualization
- Interactive 3D graphics and animations
- Secure authentication and authorization
- Financial tracking and reporting
- Student distribution analytics
- Progress tracking

### *Tech Stack*
- *Frontend*: Next.js, Tailwind CSS, Chart.js, Three.js
- *Backend*: Supabase, Clerk, Node.js
- *Database*: PostgreSQL

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd e-learning-dashboard
   
2. Install dependencies:
   bash
   npm install
   
3. Set up environment variables in .env.local.
4. Run the development server:
   bash
   npm run dev
   

---

## *4. CatalystGPT: AI Chat Comparison Platform*

A platform for comparing different AI chat models and their capabilities.

### *Features*
- Real-time AI model comparison
- Syntax highlighting for code responses
- Smooth animations and transitions
- Server-side API integration with OpenAI

### *Tech Stack*
- *Frontend*: React, Tailwind CSS, Framer Motion
- *Backend*: Node.js, Express, OpenAI SDK

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd catalystgpt
   
2. Install dependencies:
   bash
   npm install
   
3. Set up environment variables in .env.
4. Run the development server:
   bash
   npm run dev
   

---

## *5. CourseGen: AI-Powered Course Generator*

An AI-powered platform for generating comprehensive educational courses.

### *Features*
- AI-powered course content generation
- Customizable curriculum structure
- Interactive assessments and quizzes
- Progress tracking and analytics

### *Tech Stack*
- *Backend*: FastAPI, OpenAI GPT, PostgreSQL
- *Frontend*: React, TypeScript, Tailwind CSS

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd coursegen
   
2. Install backend dependencies:
   bash
   poetry install
   
3. Install frontend dependencies:
   bash
   cd frontend
   npm install
   
4. Run the application:
   - Backend: poetry run uvicorn app.main:app --reload
   - Frontend: npm run dev

---

## *6. FLUSK Image Generation Application*

A web-based application for generating high-quality images from text descriptions using OpenAI's DALL-E 3 API.

### *Features*
- Text-to-image generation using DALL-E 3
- Image history and gallery view
- Prompt suggestions and examples
- Image download and sharing capabilities

### *Tech Stack*
- *Backend*: FastAPI, OpenAI API, SQLite
- *Frontend*: React, TypeScript, Tailwind CSS

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd flusk-image-gen
   
2. Install backend dependencies:
   bash
   poetry install
   
3. Install frontend dependencies:
   bash
   cd frontend
   npm install
   
4. Run the application:
   - Backend: poetry run uvicorn app.main:app --reload
   - Frontend: npm run dev

---

## *7. E-Library Management System*

A web-based digital library platform for managing and interacting with digital books and educational resources.

### *Features*
- User authentication and authorization
- Digital book management
- Reading progress tracking
- Bookmarking system
- Admin panel for content management

### *Tech Stack*
- *Backend*: FastAPI, PostgreSQL, Redis
- *Frontend*: React, TypeScript, Tailwind CSS

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd e-library
   
2. Install backend dependencies:
   bash
   pip install -r requirements.txt
   
3. Install frontend dependencies:
   bash
   cd frontend
   npm install
   
4. Run the application:
   bash
   docker-compose up
   

---

## *8. Interactive Whiteboard Application*

A real-time collaborative whiteboard application for drawing and sharing ideas.

### *Features*
- Real-time collaborative drawing
- Multiple drawing tools (pen, shapes, text, eraser)
- Canvas manipulation (zoom, pan, undo/redo)
- User presence indicators

### *Tech Stack*
- *Frontend*: React, Fabric.js, Tailwind CSS
- *Backend*: Node.js, Express, Socket.io
- *Database*: MongoDB, Redis

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd whiteboard
   
2. Install frontend dependencies:
   bash
   cd client
   npm install
   
3. Install backend dependencies:
   bash
   cd server
   npm install
   
4. Run the application:
   - Backend: npm run dev
   - Frontend: npm run dev

---

## *9. ChatHub: Multi-Model AI Chat Application*

A feature-rich chat application that combines multiple AI models for an enhanced chat experience.

### *Features*
- Multi-model AI chat support (Anthropic, OpenAI, Google AI)
- Rich text editing capabilities
- Real-time data fetching and updates
- User authentication

### *Tech Stack*
- *Frontend*: Next.js, Tailwind CSS, Radix UI
- *Backend*: Supabase, Next.js API Routes

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd chathub
   
2. Install dependencies:
   bash
   npm install
   
3. Run the development server:
   bash
   npm run dev
   

---

## *10. Document AI App*

A document processing application that allows users to interact with PDF documents using AI.

### *Features*
- Document summarization
- Translation of document content
- Interactive Q&A with documents
- Text-to-speech conversion

### *Tech Stack*
- *Frontend*: Streamlit
- *Backend*: Python, OpenAI, PyPDF2

### *Setup*
1. Clone the repository:
   bash
   git clone <repository-url>
   cd document-ai
   
2. Create a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate
   
3. Install dependencies:
   bash
   pip install -r requirements.txt
   
4. Run the application:
   bash
   streamlit run app.py
   

---

## *11. Additional Functionalities*
- *Video Call*: Real-time video conferencing using WebRTC.
- *Interview Taker*: AI-powered interview simulation with feedback.
- *Resume Maker*: AI-assisted resume builder with templates.
- *Landing Pages*: Customizable landing page generator.
- *Prompt to Code Editor*: AI-powered code generation from natural language prompts.
- *Finance Tracker*: Personal finance management with AI insights.

---

## *License*
All projects are licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## *Contributing*
Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md) for details.

---

## *Contact*
For support or queries, please open an issue in the repository or email [jsupriti3434@gmail.com].
