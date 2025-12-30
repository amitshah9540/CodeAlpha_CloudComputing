# Cloud Computing & Security Internship Projects

This repository documents the tasks completed during my **CodeAlpha Cloud Computing Internship**. These projects demonstrate practical applications of cloud AI integration, backend security, and data pipeline management.

## 📂 Project Directory

### 1. Data Redundancy Removal System
**Location:** `/Task_DataRedundancy`

A data preprocessing utility designed to sanitize datasets before storage. In cloud environments, storage optimization is critical; this tool ensures only unique records are maintained.

* **Core Functionality:** Scans inputs to identify and remove duplicate records based on multi-column criteria.
* **Key Features:**
    * Automated detection of duplicate entries.
    * Data cleaning pipeline to standardize formatting.
    * Reduces database storage footprint by eliminating redundant copies.
* **Tech Stack:** Python, Pandas.

### 2. SQL Injection & Data Leak Prevention
**Location:** `/Task_SqlInjection`

A security-first backend module demonstrating defense-in-depth strategies. This project focuses on mitigating top web vulnerabilities related to database integrity.

* **Core Functionality:** A secure authentication system that sanitizes all user inputs.
* **Key Features:**
    * **SQL Injection Defense:** Uses **Prepared Statements** to treat user input strictly as data.
    * **Data Encryption:** Implements **AES-256** to encrypt sensitive fields before database storage.
* **Tech Stack:** Python, MySQL, Cryptography libraries.

### 3. Cloud-Powered AI Chatbot (Gemini 2.5 Flash)
**Location:** `/Task_Chatbot`

A fully generative chatbot integrated with **Google Gemini 2.5 Flash**. This project demonstrates serverless cloud inference, where heavy AI computations are offloaded to Google Cloud servers rather than running locally.

* **Core Functionality:** A Flask backend receives user messages, routes them to the Gemini API, and returns instant AI-generated responses.
* **Key Features:**
    * **Cloud AI:** Powered by Google Gemini API (running on Google Cloud).
    * **Frontend:** Clean, responsive Web UI built with HTML, CSS, and JS.
    * **Backend:** Lightweight Flask server for handling API requests.
* **Cloud Computing Role:** * Demonstrates **Serverless Cloud Inference**.
    * All processing happens on Google's infrastructure, not the local machine.

---

## 🛠️ Technology Stack

* **AI & Cloud:** Google Gemini 2.5 Flash API, Google Cloud Platform.
* **Backend:** Python (Flask), MySQL, Supabase.
* **Frontend:** HTML, CSS, JavaScript.
* **Security:** AES-256 Encryption.

---

## 🚀 Setup Instructions

### General Setup
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/codealpha-tasks.git](https://github.com/yourusername/codealpha-tasks.git)
    cd codealpha-tasks
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Specific Setup for AI Chatbot
To run the Gemini Chatbot, you must configure your API keys:

1.  **Navigate to the folder:**
    ```bash
    cd Task_Chatbot
    ```
2.  **Environment Configuration:**
    Create a `.env` file (copy from `.env.example` if available) and add your key:
    ```env
    GEMINI_API_KEY=YOUR_ACTUAL_API_KEY
    ```
3.  **Run the Server:**
    ```bash
    python chatbot.py
    ```
4.  **Access the UI:**
    Open `index.html` in your browser (or use VS Code Live Server).

---

## 🎓 Learning Outcomes

* **Cloud AI Integration:** Connecting web applications to external Cloud AI services (Gemini).
* **Cybersecurity:** Implementing rigorous validation and encryption standards.
* **Data Engineering:** Writing efficient algorithms for data quality assurance.