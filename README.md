# 🤖 AI-Powered Customer Support Chatbot

An intelligent, context-aware conversational AI assistant designed for customer service automation. The system leverages Natural Language Processing (NLP) and Deep Learning to classify user intents and return accurate, automated responses via a responsive graphical user interface.

## 🚀 Key Features

- **Intent Recognition:** Deep Neural Network model trained to accurately classify customer queries.
- **NLP Preprocessing:** Text tokenization, lemmatization, and vectorization pipelines.
- **Interactive GUI:** Built with Python's Tkinter framework (`ui.py`) for real-time conversation and debugging.
- **Customizable Knowledge Base:** Structured JSON configuration (`intents.json`) allowing easy expansion of dialog tags, patterns, and responses.

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.x
- **Deep Learning / Frameworks:** TensorFlow / Keras, Scikit-learn
- **NLP & Processing:** NLTK, Pickle
- **GUI:** Tkinter

## 📂 Project Architecture

├── intents.json        # Dataset containing intent tags, patterns, and responses
├── train.py            # Neural network training script & model generation
├── chatbot_model.h5    # Serialized trained deep learning model
├── vectorizer.pkl      # Saved text vectorizer
├── encoder.pkl         # Label encoder mapping classes
├── chat.py             # Inference pipeline & response logic
└── ui.py               # Graphical desktop interface

## 💻 Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Malathi014/Ai-customer-support-chatbot-NM.git
   cd Ai-customer-support-chatbot-NM
   ```

2. **Install Dependencies:**
   ```bash
   pip install tensorflow nltk scikit-learn
   ```

3. **Train the Model (Optional):**
   ```bash
   python train.py
   ```

4. **Launch the Application:**
   ```bash
   python ui.py
   ```
