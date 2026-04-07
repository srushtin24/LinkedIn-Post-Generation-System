# Few-Shot LLM-Based LinkedIn Post Generation System

An intelligent content generation system that leverages **few-shot learning with Large Language Models (LLMs)** to generate high-quality, style-consistent LinkedIn posts based on user-defined parameters such as topic, tone, and length.



## 🚀 Overview

This project implements a **few-shot prompt engineering pipeline** where the model is guided using curated examples from real-world LinkedIn posts. By dynamically selecting relevant examples, the system ensures that generated content closely matches desired writing styles and engagement patterns.

Unlike generic text generators, this system focuses on **style conditioning and controlled generation**, making it suitable for professional content creation.



## ✨ Key Features

- 🔹 **Few-Shot Learning Pipeline**
  - Dynamically injects example posts into prompts to guide LLM output

- 🔹 **Style-Aware Content Generation**
  - Mimics tone, structure, and engagement patterns of real LinkedIn posts

- 🔹 **Parameterized Generation**
  - Supports control over:
    - Topic
    - Tone
    - Length

- 🔹 **Data-Driven Prompting**
  - Uses structured dataset of posts for better contextual grounding

- 🔹 **Interactive UI**
  - Built using Streamlit for real-time post generation



## 🧠 System Architecture

User Input (Topic, Tone, Length)<br>
↓<br>
Example Retrieval (Few-Shot Selection)<br>
↓<br>
Prompt Construction (Examples + Instructions)<br>
↓<br>
LLM (via API)<br>
↓<br>
Generated LinkedIn Post<br>
↓<br>
Streamlit UI<br>



## 🛠️ Tech Stack

- **Language:** Python  
- **LLM Integration:** Groq / OpenAI API  
- **Framework:** Streamlit  
- **Prompt Engineering:** Few-shot learning  
- **Data Processing:** Pandas / JSON handling  



## ⚙️ How It Works

1. User provides:
   - Topic
   - Tone
   - Desired length

2. System:
   - Filters and selects relevant example posts
   - Constructs a few-shot prompt

3. LLM:
   - Generates a post based on examples and instructions

4. Output:
   - High-quality LinkedIn-ready content
<br>

## 🚀 Future Improvements

Integrate vector database (RAG + few-shot hybrid)<br>
Add engagement scoring model<br>
Introduce multi-agent refinement pipeline<br>
Build FastAPI backend for production deployment<br>
