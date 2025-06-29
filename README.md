# GenAI-Cold-Email-Generator
# Cold Email Generator

A smart Cold Email Generator built using **GROQ LLM**, **LangChain**, **Streamlit**, and **ChromaDB**. Designed specifically for service-based companies, this tool automates personalized cold outreach based on real-time job listings.

---

## Overview

This tool allows users to input the URL of a company’s **careers page**. It scrapes the job listings from that page and generates **tailored cold emails**, which include relevant portfolio links matched from a **vector database** based on the job descriptions.

> **Example Use Case:**  
> Nike is hiring a *Principal Software Engineer*. Instead of competing in hiring, **Atliq**, a software development firm, wants to offer dedicated engineers to Nike. Using this tool, Atliq’s business development executive (Mohan) can generate a highly personalized cold email to pitch their services directly.

---

## Tech Stack

- [LangChain](https://www.langchain.com/)
- [GROQ LLM](https://console.groq.com/keys)
- [Streamlit](https://streamlit.io/)
- [ChromaDB](https://www.trychroma.com/) – for storing and querying portfolio vectors

---

## Architecture Diagram

 ![Cold Email Generator Architecture](./architecture.png)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/codebasics/project-genai-cold-email-generator.git
cd project-genai-cold-email-generator
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

- Get your GROQ API key from: [https://console.groq.com/keys](https://console.groq.com/keys)
- Create a `.env` file inside the `app/` folder and add the following:

```
GROQ_API_KEY=your_api_key_here
```

### 4. Run the Streamlit App

```bash
streamlit run app/main.py
```

---

## 🛠 Features

- ✅ Extract job listings from any public careers page
- ✅ Generate personalized cold emails tailored to each job role
- ✅ Link relevant portfolio projects using ChromaDB vector search
- ✅ Built with modern GenAI tools (LangChain, LLMs, Streamlit)

---

## 📜 License

Licensed under the [MIT License](https://opensource.org/licenses/MIT).  
However, please note:

> 🔒 **Commercial use is strictly prohibited** without prior written permission from the author.  
> ✍️ **Attribution is required** in all copies or substantial portions of the software.

---

## 📁 About the Project

This project showcases how **Llama3.1 LLM**, **LangChain**, and **vector search** can automate lead generation and client outreach for B2B service companies. By combining NLP with business context, it bridges the gap between job postings and custom outreach at scale.

---

## 🙌 Credits

Developed and maintained by [Codebasics](https://github.com/codebasics)

---

## 📌 Tags & Hashtags

```
#Python #LLM #LangChain #GROQ #Streamlit #ColdEmail #ChromaDB #AI4Sales #BusinessDevelopment #VectorSearch #AIProject #LeadGeneration
```

---

## 🔗 Project Link

🌐 GitHub Repo: [https://github.com/codebasics/project-genai-cold-email-generator](https://github.com/codebasics/project-genai-cold-email-generator)
