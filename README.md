# 🧚 AI Storytelling For Kids

Welcome to AI Storytelling For Kids – an interactive storytelling platform that uses AI to generate age-appropriate fairytales with morals and questions to nurture young minds! This project integrates language understanding, educational insights, and moral reasoning using the FairytaleQA dataset, Age of Acquisition data, and transformer models.

## ✨ Overview

AI Storytelling For Kids creates magical experiences where technology meets imagination. Our platform:
- 📚 Adapts vocabulary based on a child's age
- 🔮 Generates unique stories with educational value
- 🧩 Creates interactive questions to boost comprehension
- 🛡️ Ensures content is both entertaining and developmentally appropriate

## 🚀 Features

- **Age-Appropriate Content:** Filters vocabulary using Age of Acquisition data to ensure stories match the child's development level
- **Smart Story Retrieval:** Embeds stories using Sentence Transformers and indexes them with FAISS for lightning-fast semantic search
- **Interactive Storytelling:** Responsive Gradio UI for generating and displaying fairytales in real-time
- **Educational Value:** Automatically generates comprehension questions and moral lessons
- **Personalization:** Adapts stories based on child's interests and preferences

## 🛠️ Technology Stack

- **Data Sources:**
  - FairytaleQA dataset for narrative foundations
  - Age of Acquisition lexical data for vocabulary control
  
- **AI/ML Components:**
  - Sentence Transformers for semantic understanding
  - FAISS for efficient similarity indexing
  - Retrieval-Augmented Generation (RAG) architecture
  - Groq LLM integration for story generation

## 📋 Installation

### Prerequisites
- Python 3.8+
- Git

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Maitri-Shekhda/AI-Storytelling-For-Kids.git
   cd AI-Storytelling-For-Kids
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
   Or install major dependencies manually:
   ```bash
   pip install pandas numpy sentence-transformers faiss-cpu gradio groq
   ```

3. **Configure API key:**
   ```bash
   export GROQ_API_KEY="your_api_key_here"
   ```

## 🎮 Usage

### Running the Notebook

```bash
jupyter notebook ai_story_teller.ipynb
```

Follow the notebook cells to:
1. Process datasets and prepare story corpus
2. Create FAISS indexes for efficient retrieval
3. Initialize the StoryRAG system
4. Generate interactive stories

### Using the Web Interface

After running the notebook, the Gradio UI will allow you to:
- Input a child's age
- Specify interests or themes
- Generate custom fairytales
- Explore educational questions and moral lessons


``

## 📸 Screenshots




## 🙏 Acknowledgements

- [FairytaleQA Dataset](https://github.com/uci-soe/FairytaleQA) - For providing the foundation of our story corpus
- [Age of Acquisition Dataset](https://psyarxiv.com/9ckbw/) - For age-appropriate vocabulary filtering
- [HuggingFace Transformers](https://huggingface.co/transformers/) - For state-of-the-art NLP models
- [Gradio](https://gradio.app/) - For the intuitive user interface
- [Groq](https://groq.com/) - For powerful LLM inference capabilities

