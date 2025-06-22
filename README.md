

# Next Word Prediction with LSTM

## 📌 Project Overview

This project presents a **Next Word Prediction** system built using a **Long Short-Term Memory (LSTM)** neural network, developed with **TensorFlow** and **Keras**. The model is trained on the full text of *The Tragedy of Hamlet* by William Shakespeare to predict the next word given a sequence of input words.

The application features an interactive **Streamlit web interface** for real-time word prediction and is deployed in an environment managed by **Anaconda** to ensure reproducibility and clean dependency management.

---

## ✨ Key Features

* **LSTM-Based Model:** Employs a powerful sequence model using LSTM layers for accurate next-word prediction.
* **Text Tokenization:** Utilizes a Keras tokenizer to convert raw text into integer sequences suitable for neural network input.
* **Streamlit Interface:** Delivers an intuitive and responsive front-end for user interaction and live predictions.
* **Early Stopping:** Integrates early stopping during training to reduce overfitting and improve generalization.
* **Pre-Trained Components:** Includes a pre-trained model (`next_word_lstm.h5`) and tokenizer (`tokenizer.pickle`) for quick deployment.

---

## ⚙️ Prerequisites

* **Python:** Version 3.11
* **Anaconda:** For virtual environment and dependency management
* **Dependencies:** Specified in `requirements.txt`

---

## 🚀 Installation Guide

Follow the steps below to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create and Activate a Virtual Environment

```bash
conda create -n next_word_prediction python=3.11
conda activate next_word_prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Verify Installation

```bash
python -m streamlit --version
```

---

## 🧠 Usage Instructions

### Launch the Streamlit App

```bash
streamlit run app.py
```

> This will open the app in your default web browser, usually at `http://localhost:8501`.

### Using the App:

1. Enter a phrase (e.g., `To be or not to`) in the input box.
2. Click on **"Predict Next Word"**.
3. The predicted word will appear below the input field.

---

## 🗂️ Project Structure

```
├── app.py                  # Streamlit web application
├── hamlet.txt              # Training corpus (Hamlet by Shakespeare)
├── next_word_lstm.h5       # Trained LSTM model
├── tokenizer.pickle        # Serialized Keras tokenizer
├── requirements.txt        # Dependency list
└── README.md               # Project documentation
```

---

## 📦 Dependencies

The project depends on the following Python packages:

* `tensorflow==2.15.0` – Deep learning framework
* `numpy` – Numerical operations
* `pandas` – Data handling (optional)
* `scikit-learn` – Machine learning utilities
* `scikeras` – Scikit-learn wrapper for Keras
* `tensorboard` – Training visualization
* `matplotlib` – Visualization (optional)
* `streamlit` – Web interface
* `ipykernel` – Jupyter support (optional)

> All dependencies are listed in the `requirements.txt` file.

---

## 🧬 Model Architecture

* **Training Data:** Text from *Hamlet* (`hamlet.txt`)
* **Tokenizer:** Pre-trained Keras tokenizer for word-to-index mapping
* **Input Format:** Tokenized and padded sequences of words
* **Model:** LSTM-based neural network
* **Output:** Predicts the most probable next word based on context

---

## 💻 Development Environment

* **Python Version:** 3.11
* **Environment Manager:** Anaconda
* **Recommended IDEs:** VS Code, PyCharm, Jupyter Notebook
* **Operating Systems:** Compatible with Windows, macOS, and Linux

---

## 🤝 Contributing

Contributions are highly encouraged! To contribute:

1. Fork the repository
2. Create a feature branch

   ```bash
   git checkout -b feature-branch
   ```
3. Make changes and commit

   ```bash
   git commit -m "Add new feature"
   ```
4. Push your changes

   ```bash
   git push origin feature-branch
   ```
5. Open a pull request

> Please adhere to **PEP 8** guidelines and ensure proper documentation.

---

## Acknowledgments

* *William Shakespeare* – For the source text (*The Tragedy of Hamlet*)
* **TensorFlow & Keras** – For providing the deep learning tools
* **Streamlit** – For enabling rapid and elegant UI development

---

## 📬 Contact

For questions, suggestions, or issues, please open an issue in the repository or contact the project maintainer.

"# NEXT-WORD-PREDICTION-USING-LSTM-DL-PROJECT" 
