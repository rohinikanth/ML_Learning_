# 🩺 First Aid Chatbot using Deep Learning

This project implements a **basic first aid chatbot** that provides medical assistance for common symptoms like fever, headache, diarrhea, cough, wounds, stress, etc., based on user input. It uses a deep learning model trained on labeled health-related conversation data to generate relevant and context-aware responses.

---

## Features

* Context-aware chatbot for first aid queries.
* Deep learning-based text classification and response generation.
* Trained on custom data for medical first aid intents.
* Visualized training metrics (accuracy, loss).
* Provides basic treatments or first response suggestions (e.g., CPR steps, remedies for cough, fever, etc.).

---

##Use Case

> A simple AI-based assistant for preliminary **health advice**, useful for:

* Educational apps.
* Health awareness tools.
* Early symptom guidance before visiting a doctor.
* Emergency aid instructions (e.g., CPR, bleeding, nosebleeds).

---

##Tech Stack

| Component      | Description                                          |
| -------------- | ---------------------------------------------------- |
| **Language**   | Python                                               |
| **Libraries**  | TensorFlow / Keras, NumPy, Matplotlib, Scikit-learn  |
| **Model Type** | Text Classification Neural Network                   |
| **Interface**  | Console-based Chat Interaction                       |
| **Data**       | Custom health-related Q\&A pairs for common symptoms |

---

##Model Performance

| Metric                   | Train    | Test     |
| ------------------------ | -------- | -------- |
| Accuracy                 | 99.70%   | 98.82%   |
| Mean Squared Error (MSE) | 0.000024 | 0.000118 |
| Root MSE (RMSE)          | 0.0049   | 0.0108   |

## 🧪 How It Works

1. **Preprocessing**: Tokenizes and vectorizes input sentences.
2. **Training**: A text classification model learns to map user inputs to intent categories.
3. **Response Generation**: Maps predicted intent to a predefined response.
4. **Interactive Session**: Accepts user input in a loop and replies with the appropriate medical advice.

##Getting Started
### Prerequisites

```bash
pip install tensorflow numpy matplotlib scikit-learn
python chatbot.py #running the chatbot
```

###Sample Interaction

```
You: I have a headache
🤖 Chatbot: Give ibuprofen (Advil, Motrin), aspirin, or acetaminophen (Tylenol) for pain...

You: How to perform CPR?
🤖 Chatbot: 1) Place the heel of one hand on the center of the chest...
```

---

## Limitations & Improvements

* **Not a replacement for professional medical help.**
* May misunderstand rare or misphrased symptoms.
* Future improvements:

  * Integrate NLP models like BERT or GPT for better understanding.
  * Add speech recognition and text-to-speech for accessibility.
  * Expand dataset to cover more conditions and languages.

---
