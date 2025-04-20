# 🧚 AI Storytelling For Kids

Welcome to **AI Storytelling For Kids** – an interactive storytelling platform that uses AI to generate age-appropriate fairytales with morals and questions to nurture young minds! This project integrates language understanding, educational insights, and moral reasoning using the **FairytaleQA dataset**, **Age of Acquisition data**, and **transformer models**.

---

## 🚀 Features

- Loads and processes the FairytaleQA dataset to extract complete stories.
- Filters vocabulary using Age of Acquisition to ensure content is suitable for the child’s age.
- Embeds stories using Sentence Transformers and indexes them using FAISS.
- Retrieves relevant story sections based on semantic similarity to user input.
- Interactive Gradio UI for generating and displaying fairytales in real-time.

---

## Installation
Clone the repository:
git clone https://github.com/Maitri-Shekhda/AI-Storytelling-For-Kids.git
cd AI-Storytelling-For-Kids

Install the required dependencies:
pip install -r requirements.txt

Or install them manually:
pip install pandas numpy sentence-transformers faiss-cpu gradio groq

Set up your Groq API key:
export GROQ_API_KEY="your_api_key_here"

--

## Running the Notebook
Open the Jupyter notebook:

bash
jupyter notebook ai_story_teller.ipynb

Run the cells sequentially to:

Process the datasets

Create FAISS indexes for fast retrieval

Initialize the StoryRAG system

Generate and interact with stories

--


## 🙏 Acknowledgements
FairytaleQA Dataset

AoA Dataset

HuggingFace Transformers

Gradio for the UI

