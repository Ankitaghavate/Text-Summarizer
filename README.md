# 🧠 Text Summarizer using T5 & FastAPI

## 📌 Overview

This project is a **Text Summarization Web Application** built using a fine-tuned **T5 Transformer model**.
It takes long dialogues or text as input and generates a concise summary.

---

## 🚀 Features

* 🔹 Text summarization using Transformer (T5)
* 🔹 Clean and responsive web UI
* 🔹 FastAPI backend for real-time inference
* 🔹 Preprocessing + tokenization pipeline
* 🔹 Beam search for better summary generation

---

## 🏗️ Tech Stack

* **Python**
* **FastAPI**
* **HuggingFace Transformers**
* **PyTorch**
* **HTML, CSS, JavaScript**

---

## 📂 Project Structure

```
Text Summarizer/
│
├── app.py                 # FastAPI backend
├── index.html             # Frontend UI
├── saved_summary_model/   # Trained T5 model
│   ├── config.json
│   ├── model.safetensors
│   ├── tokenizer.json
│   └── ...
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
```

### 2️⃣ Install dependencies

```
pip install fastapi uvicorn transformers torch
```

### 3️⃣ Run the application

```
uvicorn app:app --reload
```

---

## 🌐 Usage

### 👉 Open in browser:

```
http://127.0.0.1:8000
```

### 👉 API Docs:

```
http://127.0.0.1:8000/docs
```

---

## 🧪 Example

### Input:

```
A: Hi, how are you?
B: I'm fine. Let's meet tomorrow.
```

### Output:

```
They plan to meet tomorrow.
```

---

## 🧠 Model Details

* Model: **T5 (Text-to-Text Transfer Transformer)**
* Fine-tuned on: **SAMSum Dataset**
* Task: **Dialogue Summarization**
* Generation Method: **Beam Search (num_beams=4)**

---

## 📈 Future Improvements

* 🔹 Add ROUGE score evaluation
* 🔹 Support PDF / file summarization
* 🔹 Deploy on cloud (Render / AWS)
* 🔹 Improve model accuracy with larger dataset
* 🔹 Add user authentication

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👩‍💻 Author

**Ankita Ghavate**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
