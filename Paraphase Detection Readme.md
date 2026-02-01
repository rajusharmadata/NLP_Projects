
# 🧠 Sentence Similarity & Paraphrase Detection Project

## 📌 Project Overview
This project implements **semantic sentence similarity and paraphrase detection** using modern NLP embedding models from Sentence Transformers.

The system converts sentences into vector embeddings and computes similarity scores using cosine similarity. It can also automatically find similar sentence pairs from a list.

This project demonstrates practical NLP skills useful in real-world AI applications such as search engines, chatbots, recommendation systems, and duplicate content detection.

---

## 🚀 Features
- Compare similarity between two sentences
- Detect paraphrased sentences automatically
- Generate sentence embeddings
- Compute cosine similarity scores
- Mine similar sentences from datasets
- Clean and reusable Python implementation
- Notebook-ready and script-ready code

---

## 🛠 Tech Stack
- Python
- PyTorch
- Sentence Transformers
- HuggingFace Transformers
- Jupyter Notebook

---

## 📂 Project Structure
```

project/
│── notebook.ipynb          # Main Jupyter notebook
│── similarity.py            # Clean Python script (optional)
│── README.md                # Project documentation
│── requirements.txt         # Dependencies

````

---

## ⚙️ Installation
Install required dependencies:

```bash
pip install sentence-transformers torch
````

Or install using requirements file:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Step 1 — Import Model

The project loads a pretrained Sentence Transformer model.

### Step 2 — Encode Sentences

Sentences are converted into embeddings.

### Step 3 — Compute Similarity

Cosine similarity is computed between embeddings.

### Step 4 — Paraphrase Mining

The system identifies similar sentence pairs automatically.

---

### Example Code Usage

```python
score = sentence_similarity(
    "The cat sits outside",
    "The cat plays in the garden"
)

print(score)
```

---

## 📊 Example Output

```
Sentence 1: The new movie is awesome
Sentence 2: The new movie is so great
Similarity Score: 0.8939
```

Higher scores mean higher semantic similarity.

---

## 🎯 Applications

This technique is widely used in:

* Chatbots & Virtual Assistants
* Search Engines
* Duplicate Question Detection
* Document Clustering
* Content Recommendation
* Semantic Search Systems
* AI Assistants

---

## 💡 Learning Outcomes

This project demonstrates:

* NLP embeddings
* Semantic similarity measurement
* Transformer model usage
* Cosine similarity
* Practical NLP implementation

---

## 🔮 Future Improvements

Possible enhancements:

* Web interface using Streamlit
* REST API using FastAPI
* Large dataset processing
* Real-time similarity search
* Database storage for embeddings
* Deployment as web service

---

## 👨‍💻 Author

**Raju Kumar**
B.Tech Computer Science Student
Aspiring Software Developer & AI Enthusiast

---

## 📜 License

This project is open-source and free to use for educational and development purposes.

---

## ⭐ Support

If you found this useful, consider starring the repository on GitHub.

```

If you want, next we can make a **resume-ready version** or improve it to impress recruiters.
```
