# 🛡️ Unified AI-Driven Multi-Modal System for Fake Content Detection and Trust-Based User Behavior Analysis

### An AI-powered platform to identify fake and misleading digital content using Text, Image and Audio analysis.

---

## 📌 Project Overview

The rapid growth of social media and digital platforms has increased the spread of misinformation, fake news, manipulated images and misleading audio content.

This project introduces a Unified AI-Driven Multi-Modal System that detects fake and misleading content using Artificial Intelligence and Deep Learning techniques.

The system analyzes user-submitted text, images and audio, classifies the content as Genuine or Fake, and provides understandable explanations along with supporting web sources.

It also incorporates trust-based user behavior analysis to identify repeated misinformation contributors and encourage responsible content sharing.

---

## 🎯 Objectives

- Develop an AI-powered multi-modal fake content detection system.
- Analyze text, images and audio using specialized AI models.
- Classify submitted content as Genuine or Fake.
- Generate understandable explanations for detection results.
- Retrieve relevant supporting information from online sources.
- Analyze user behavior and maintain trust-based profiles.
- Encourage responsible digital communication.

---

## ✨ Key Features

### 1. Multi-Modal Fake Content Detection
Supports three content modalities:

- **Text Detection:** Identifies misleading and fake textual information.
- **Image Detection:** Analyzes images to identify manipulated or AI-generated content.
- **Audio Detection:** Processes audio recordings and identifies suspicious or artificially generated content.

### 2. AI-Based Classification
Uses specialized deep learning models to classify content and generate detection results.

### 3. Explainable AI
Provides human-readable explanations to help users understand why content is classified as genuine or fake.

### 4. Live Web Verification
Uses Tavily API to retrieve relevant online information and supporting sources for content verification.

### 5. OCR-Based Text Extraction
Extracts textual information from images to support content verification.

### 6. Trust-Based User Behavior Analysis
Analyzes user activity and content submission patterns to support credibility assessment.

### 7. User-Friendly Interface
Provides an interactive interface for submitting content and viewing detection results.

---

## 🧠 Technologies & Models Used

| Technology | Purpose |
|---|---|
| Python | Core programming and AI implementation |
| RoBERTa | Text classification |
| ResNet50 | Image analysis |
| Whisper | Audio transcription and processing |
| OCR | Text extraction from images |
| Tavily API | Live web search and source retrieval |
| FastAPI | Backend development and API integration |
| React.js | Frontend development |
| Vite | Frontend development environment |
| Browser Extension (Manifest V3) | Browser-based integration |

---

## 🏗️ System Architecture

The system follows a multi-stage processing architecture.

1. **User Input:** Users submit text, images or audio.
2. **Preprocessing:** Input data is cleaned and prepared for analysis.
3. **AI Model Processing:**
   - RoBERTa processes textual content.
   - ResNet50 analyzes image content.
   - Whisper processes audio recordings.
   - OCR extracts text from images.
4. **Content Verification:** Tavily API retrieves relevant online information.
5. **Classification:** The system generates Genuine or Fake predictions.
6. **Explainability:** Provides understandable reasons behind the prediction.
7. **Result Display:** Displays the classification, explanation and supporting sources.

---

## 🔄 Working Methodology

**Step 1:** User uploads text, image or audio content.

**Step 2:** The system identifies the input modality and performs preprocessing.

**Step 3:** The corresponding AI model analyzes the submitted content.

**Step 4:** OCR and web verification are used where applicable to obtain additional information.

**Step 5:** The system generates the classification result.

**Step 6:** An explanation and relevant supporting sources are presented to the user.

---

## 📂 Project Structure

The project is organized into frontend, backend and AI processing components.

```text
Project/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── main.py
│   ├── models/
│   ├── routes/
│   └── requirements.txt
│
├── browser-extension/
│
├── datasets/
│
├── README.md
└── .gitignore
```

*Note: The above is an illustrative structure. Adjust the folder names to match your actual project.*

---

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.x
- Node.js and npm
- Git
- Required API credentials

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project

```bash
cd YOUR_PROJECT_FOLDER
```

### 3. Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

Configure the required environment variables and API credentials.

Start the FastAPI server using your project's configured startup command.

### 4. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### 5. Access the Application

Open the local frontend URL displayed by Vite in your browser.

*Note: Update these commands according to your actual project configuration.*

---

## 🌍 Sustainable Development Goals (SDGs)

This project contributes to the following United Nations Sustainable Development Goals:

- **SDG 16 – Peace, Justice and Strong Institutions:** Helps reduce misinformation and encourages accountability.
- **SDG 4 – Quality Education:** Promotes digital awareness and information literacy.
- **SDG 3 – Good Health and Well-being:** Helps identify misleading health-related information.
- **SDG 9 – Industry, Innovation and Infrastructure:** Promotes innovative AI-based digital solutions.

---

## 🚀 Future Enhancements

- Expand detection capabilities to additional languages.
- Improve detection accuracy through advanced multimodal fusion.
- Enhance real-time content verification.
- Extend platform integrations.
- Improve user credibility assessment.
- Enhance model explainability and performance.

---

## 👨‍💻 Project Contributors

**Bachelor of Engineering – Computer Science and Engineering**

B.M.S. College of Engineering, Bengaluru

- Madhan K
- Mahesh Lamani
- Praveen Rathod
- Roshan N

**Project Guide:** Ambuja K  
Assistant Professor, Department of CSE, BMSCE.

**Academic Year:** 2026–2027

---

## 📄 License

This project was developed as an academic major project. Contact the project contributors before reusing or distributing its source code.

---

### ⭐ If you find this project interesting, feel free to explore the repository!
