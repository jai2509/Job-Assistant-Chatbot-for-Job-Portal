# Job Assistant Chatbot for Job Portal (Minor Project)

## Overview
This is a **Job Assistant Chatbot** designed to help users find job recommendations based on their resumes. It leverages **Large Language Models (LLMs)** and is implemented using **Retrieval-Augmented Generation (RAG)**. The chatbot processes resumes, extracts relevant job-related skills, and provides job suggestions accordingly.

## Team & Contributors
This project was developed as part of our **Minor Project Submission** by the following team members:
- **Tushti Joshi** (Conversational AI & GROQ Model Integration)
- **Jai Kumar Mishra** (Backend & Data Processing, LangChain Setup, FAISS Integration)
- **Vidhushi Sain** (Frontend & UI Design, Streamlit Integration)
- **Sahil Aggarwal** (Testing, Performance Optimization & Documentation)

## Features
- **Resume Parsing:** Extracts skills, job roles, and keywords from uploaded PDFs.
- **NLP-Based Query Handling:** Uses an intelligent chatbot to answer job-related queries.
- **Job Recommendations:** Fetches job listings based on extracted skills via **Jooble API**.
- **Conversational Memory:** Maintains chat history for a seamless experience.
- **RAG Implementation:** Enhances response generation by retrieving relevant context.
- **User-Friendly Interface:** Built using **Streamlit** for an intuitive experience.

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python, LangChain, FAISS, GROQ API
- **Libraries & Tools:**
  - PyPDF2 (Resume Parsing)
  - HuggingFace Embeddings (Text Vectorization)
  - FAISS (Efficient Semantic Search)
  - LangChain (Conversational AI & RAG)
  - ChatGroq (LLM Integration)
  - Jooble API (Job Fetching)

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/job-assistant-chatbot.git
   cd job-assistant-chatbot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   ```bash
   export GROQ_API_KEY='your_groq_api_key'
   export JOOBLE_API_KEY='your_jooble_api_key'
   ```
4. Run the application:
   ```bash
   streamlit run app_test.py
   ```

## Usage
- Upload your resume (PDF format).
- Ask career-related queries.
- Get job recommendations based on skills extracted from your resume.
- Interact with the chatbot for personalized job assistance.

## Future Enhancements
- Expand support for more document formats.
- Optimize response time and resource usage.
- Improve job recommendation accuracy using **advanced NLP models**.
- Introduce voice-activated interaction.

## Contributors & Contact
Feel free to connect with us:
- **Tushti Joshi** - [LinkedIn](https://www.linkedin.com/in/tushti-joshi-899282211 )
- **Jai Kumar Mishra** - [LinkedIn](https://www.linkedin.com/in/jai-kumar-mishra-0981641aa)
- **Vidhushi Sain** - [LinkedIn](linkedin.com/in/vidhushi-sain-4a22b3270)
- **Sahil Aggarwal** - [LinkedIn](
linkedin.com/in/sahil-aggarwal-70232a1b7)

For any issues, please open an issue in the repository. 🚀

