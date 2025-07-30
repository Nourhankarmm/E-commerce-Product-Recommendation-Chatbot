# 💬 E-commerce Product Recommendation Chatbot

A chatbot designed to recommend products based on user queries using **Amazon US Customer Reviews** dataset. Combines NLP embeddings and similarity matching to respond conversationally with relevant product suggestions.

---

## ⚙️ Key Features

- Utilizes **Amazon review dataset** for recommendation
- **Text embedding** (e.g. GPT‑3.5 or embedding models) for understanding user intent
- **Similarity matching** via cosine similarity on user-input vs product descriptions
- Conversational interface: chatbot interprets queries and provides product links or suggestions

---

## 🧠 Architecture & Pipeline

- **Dataset**: Amazon reviews (titles, descriptions, ratings)
- **User Input Processing**:
  - Tokenization, vectorization using embedding model
  - Similarity search over product indices
- **Chatbot Logic**:
  - Parse request (e.g. “I'm looking for wireless earbuds”)
  - Retrieve top‑k similar products
  - Format response with product names, links, and brief descriptions

---

## 📌 Further Improvements

Fine-tune embedding model (e.g. fine-tuned transformer on product descriptions)
Use multi-modal input combining image + text embeddings
Add feedback loop for user ratings to refine future recommendations (collaborative filtering)
Deploy as API and integrate with an e‑commerce frontend



