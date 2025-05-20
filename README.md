# AI Therapist

This project is an interactive AI-powered therapist that simulates empathetic conversations. It consists of two main components:

- **Emotion Detection:** Uses a DistilBERT classifier to identify user emotions from text.
- **Response Generation:** Uses a GPT-2 model fine-tuned on therapist-style responses to provide empathetic replies.

## Project Structure

| File | Description |
|------|-------------|
| `train_emotion_model.ipynb` | Trains the emotion classification model using the Hugging Face `emotion` dataset |
| `train_therapist_response_model.ipynb` | Fine-tunes a GPT-2 model to generate therapist-style responses |
| `therapist_interview.ipynb` | Integrates both models into an interactive therapist chatbot notebook |

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PaulRo230/AI-Therapist.git
   cd AI-Therapist
