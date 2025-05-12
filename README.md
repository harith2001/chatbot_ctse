
# 🤖 CTSE Lecture Notes Chatbot

An interactive chatbot designed to answer questions based on lecture notes from the *Current Trends in Software Engineering (CTSE)* module. Built using a retrieval-based architecture with open-source tools, this chatbot runs entirely inside a Jupyter Notebook and supports semantic search over course content using MiniLM and FAISS.

---

## 📌 Features

- 📚 Converts `.pptx` lecture notes into text
- 🧠 Embeds lecture content using `MiniLM` (all-MiniLM-L6-v2)
- 🗃️ Stores embeddings in a FAISS vector database
- 🔍 Retrieves semantically relevant answers based on user questions
- 💬 Provides a clean interactive UI using `ipywidgets`
- 💻 Runs locally without the need for paid APIs (no OpenAI key required)

---

## 🛠️ Technologies Used

| Tool              | Purpose                                      |
|------------------|----------------------------------------------|
| Python 3.x        | Core language                                |
| Jupyter Notebook | Development environment                      |
| FAISS            | Vector similarity search                     |
| MiniLM           | Sentence embeddings                          |
| HuggingFace Transformers | Open-source model access         |
| ipywidgets       | Interactive input/output interface            |
| python-pptx      | PowerPoint to text conversion                 |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ctse-chatbot.git
cd ctse-chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install sentence-transformers faiss-cpu ipywidgets python-pptx
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open `CTSE_Chatbot.ipynb` and run all cells to interact with the chatbot.

---

## 📂 Folder Structure

```
📁 ctse-chatbot/
│
├── CTSE_Chatbot.ipynb       # Main chatbot notebook
├── ctse_notes.txt           # Text file converted from lecture slides
├── requirements.txt         # Python dependencies
├── README.md                # This file
├── assets/                  # (Optional) Diagram, screenshots
└── faiss_index/             # Stored vector database
```

---

## 📘 License

This project is developed as part of the SE4010 – Current Trends in Software Engineering module. Intended for educational use only.

---

## 🙋‍♂️ Author

**Harit Vithanage**  
Faculty of Computing  
[SLIIT]

---

## 🤝 Acknowledgments

- HuggingFace for MiniLM
- Facebook AI for FAISS
- Jupyter & ipywidgets team
