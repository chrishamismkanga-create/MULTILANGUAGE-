# 🌍 Development of a Multilingual Health Question Answering System for Low-Resource African Languages Using Natural Language Processing and Deep Learning

## 📖 Project Overview

This project aims to develop an **AI-powered Multilingual Health Question Answering (MHQA) System** that enables users to ask healthcare-related questions in low-resource African languages and receive accurate responses in their preferred language.

The system leverages **Natural Language Processing (NLP)**, **Transformer-based Deep Learning models**, and **Machine Translation** techniques to bridge language barriers in healthcare communication.

The project is developed as part of an academic research project in Biomedical Equipment Engineering.

---

## 🎯 Objectives

* Develop a multilingual health question answering system.
* Support low-resource African languages.
* Improve healthcare information accessibility.
* Apply Natural Language Processing techniques.
* Train and evaluate transformer-based deep learning models.
* Build a modern web application for healthcare users.

---

## 🚀 Features

* 🌍 Multilingual health question answering
* 🧠 Transformer-based NLP model
* 🔄 Machine translation support
* 🗣️ Future voice input and speech output
* 📱 Responsive web interface
* ⚡ Fast API response using FastAPI
* 🔒 Scalable architecture for future deployment

---

## 🏗️ System Architecture

                 User
                   │
                   ▼
          Streamlit Web Interface
                   │
                   ▼
      Question Processing (Python)
                   │
                   ▼
      Transformer NLP Model
     (PyTorch + Hugging Face)
                   │
                   ▼
      Answer Generation Module
                   │
                   ▼
        Multilingual Response

---

## 🛠️ Technology Stack

Proposed System Architecture

Frontend

Streamlit

Backend

Python

Artificial Intelligence

PyTorch
Hugging Face Transformers
Natural Language Processing (NLP)

Database

PostgreSQL (Future Integration)

Development Environment

Google Colab
Jupyter Notebook
Visual Studio Code
GitHub

### Version Control

* Git
* GitHub

---

## 📂 Project Structure

```text
Multilingual-Health-QA-System/
│
├── data/
│   ├──> Train.Ai.csv
│   └──> Validation.csv
│
├── notebooks/
│   ├──> Week1_EDA.ipynb
│   ├──> Week2_Preprocessing.ipynb
│   └──> Week3_ModelTraining.ipynb
│
│
├── app/
│   ├──> streamlit_app.py      # User interface
│   ├──> pages/
│   ├──> assets/
│
├── backend/
│   ├──> model.py              # Transformer model
│   ├──> inference.py          # Prediction logic
│   ├──> preprocess.py         # Text preprocessing
│   ├──> utils.py
│   └──> requirements.txt
├── models/
│   └──> trained_model/
│
├──> reports/
│
├──> README.md
│
└──> LICENSE
```

---

## 📊 Current Progress

### ✅ Week 1

* Project planning
* Dataset understanding
* Exploratory Data Analysis (EDA)
* Dataset statistics
* Data visualization

### ✅ Week 2

* Data cleaning
* Missing value handling
* Duplicate removal
* Text preprocessing
* Tokenization
* Training and validation dataset creation

### 🔄 Week 3 (In Progress)

* Train baseline multilingual transformer model
* Evaluate model performance
* Analyze prediction errors

---

## 📈 Future Improvements

* Voice-based health questions
* Speech-to-text support
* Text-to-speech responses
* More African language support
* Hospital information system integration
* Mobile application development
* Cloud deployment

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Chris Mkanga/Multilingual-Health-QA-System.git
```

Move into the project directory:

```bash
cd Multilingual-Health-QA-System
```

Install Python dependencies:

```bash
pip install -r backend/requirements.txt
```

For the frontend:

```bash
cd frontend
npm install
npm start
```

---

## 📚 Dataset

The project uses a multilingual translation dataset for training and evaluation.

Dataset includes:

* Source text
* Target text
* Language subset
* Sample identifiers

---

## 📊 Model Workflow

1. Load dataset
2. Perform exploratory data analysis
3. Clean and preprocess text
4. Tokenize sentences
5. Split training and validation datasets
6. Train transformer model
7. Evaluate performance
8. Deploy model through FastAPI
9. Access predictions through React.js frontend

---

## 🤝 Contributions

Contributions are welcome.

Please open an Issue or submit a Pull Request for suggestions or improvements.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Christopher Hamisi Mkanga**

Diploma in Biomedical Equipment Engineering

Big support with AI HUB at (MUST)

Mbeya University of Science and Technology (MUST)

Tanzania

---

## 🙏 Acknowledgements

* Mbeya University of Science and Technology (MUST)
* Hugging Face
* PyTorch
* Google Colab
* FastAPI
* React.js
* OpenAI
