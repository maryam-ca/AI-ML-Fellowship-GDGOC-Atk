# 🤖 Task 15 — Generative AI (GAN + RAG)

## 📌 Overview
This project explores key concepts of Generative AI including:
- Generative Adversarial Networks (GANs)
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)

The project demonstrates both image generation and intelligent document-based question answering.

---

# 🧠 PART 1 — GAN (Image Generation)

## 🔹 What is GAN?
A Generative Adversarial Network (GAN) consists of two models:

- **Generator** → Generates fake images  
- **Discriminator** → Identifies real vs fake images  

Both models compete with each other, improving over time.

---

## 🔹 Implementation

- Dataset: MNIST (handwritten digits)
- Framework: TensorFlow
- Generator creates images from noise
- Discriminator classifies images

---

## 🔹 Results

- Initially, generated images are random noise  
- After training, images resemble handwritten digits  
- Model improves with more epochs  

---

## 🔹 Data Augmentation using GAN

GAN can generate synthetic data to increase dataset size.

### Benefits:
- Improves accuracy  
- Reduces overfitting  
- Useful for small datasets  

---

# 🤖 PART 2 — LLM + RAG

## 🔹 What is RAG?

Retrieval-Augmented Generation combines:
- **Retrieval** → Fetch relevant data  
- **Generation** → Generate answer using LLM  

---

## 🔹 Workflow

1. Load documents  
2. Convert into vector index  
3. Query system  
4. Generate response  

---

## 🔹 Implementation Details

- Library: LlamaIndex  
- Documents loaded from local folder  
- Vector index created  
- Query engine used for answering  

---

## 🔹 Important Note

> A mock LLM and mock embedding model were used to run the system offline without requiring an external API.

---

## 🔹 Output


Artificial Intelligence is the future of technology.


---

# 📊 Technologies Used

- Python  
- TensorFlow  
- LlamaIndex  
- NumPy  
- Matplotlib  

---

# 📁 Project Structure


project/
│── data/
│ └── sample.txt
│── gan_code.py
│── rag_code.py
│── README.md


---

# 🚀 How to Run

## 🔹 GAN
1. Open Colab notebook  
2. Run all cells  
3. View generated images  

## 🔹 RAG
1. Install dependencies:

pip install llama-index

2. Run the script  
3. Ask queries  

---

# 🎯 Conclusion

This project demonstrates how GANs can generate realistic images and how RAG enhances LLMs by combining retrieval with generation. These techniques are widely used in modern AI applications.

---

# 👩‍💻 Author

**Maryam Fatima**