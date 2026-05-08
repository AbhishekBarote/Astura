# Astura - Basic Banking Chatbot

This repository contains the source code for the **AI Internship Assignment: Basic Banking Chatbot using LLM and Embeddings**.

Astura is an AI-powered banking assistant that retrieves relevant information from a specialized banking dataset and uses a Large Language Model (LLM) to generate smooth, human-like responses.

## 🌟 Features
- **Local Embeddings**: Uses `sentence-transformers` (`all-MiniLM-L6-v2`) for lightning-fast, offline vectorization of questions.
- **Intelligent RAG**: Implements Retrieval-Augmented Generation to fetch the most similar banking context using Cosine Similarity.
- **LLM Integration**: Uses Google's **Gemini 2.5** to synthesize retrieved data into natural, friendly conversational responses.
- **Context-Aware Suggestions**: Automatically generates highly relevant follow-up questions after every turn.
- **Premium UI**: Features a beautiful, buttery-smooth Streamlit interface with dark glassmorphism styling, as well as a classic Command-Line Interface (CLI).

## 🛠️ Tech Stack
- **Python**
- **Embeddings**: `sentence-transformers`
- **LLM**: `google-generativeai` (Gemini API)
- **Math/Vector ops**: `numpy`, `scikit-learn`
- **UI Framework**: `streamlit`

## 🚀 How to Run Locally

### 1. Clone the repository and navigate to the project directory:
```bash
# git clone <your-repo-url>
cd Atura
```

### 2. Install Dependencies:
```bash
pip install -r requirements.txt
```
*(Tip: If the installation times out on a slow network due to large packages, use: `pip install -r requirements.txt --default-timeout=1000`)*

### 3. Run the Streamlit UI (Recommended):
```bash
streamlit run app.py
```

### 4. Run the Command-Line Version (CLI):
```bash
python chatbot.py
```

---

## 📸 Screenshots & Sample Queries

Here are some sample interactions demonstrating the chatbot's ability to retrieve information from the dataset and generate human-like responses, as well as recommend follow-up questions.

> **Note to evaluator/user:** The images below demonstrate the working functionality of the chatbot.

### 1. Main Chat Interface
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3e33b3a3-9685-4f63-ad92-8c22d211f28f" />


### 2. Sample Query 1: "What is KYC?"
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0652b294-0e42-4765-a3bd-4fb23c6bc0fe" />


### 3. Sample Query 2: "What documents do I need to open an account?"
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/974890d0-3f5f-4859-8b4e-43e4585e5412" />


### 4. Out-of-Dataset / General Banking Query
*(Upload your screenshot to GitHub and put the link here)*
`![General Query Screenshot](insert-image-link-here)`

---
*Developed for AI Internship Assignment evaluation.*
