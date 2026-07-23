# Next-Word Prediction (LSTM)

## Concept
A **language model** predicts the next word given the preceding words — the idea behind autocomplete
and, at scale, large language models. An **LSTM** captures sequential context to make the prediction.

## Implementation
- Trains on the text of Shakespeare's **Hamlet** (via NLTK's Gutenberg corpus).
- Tokenizes the text, builds input sequences, and trains an **LSTM** model (Keras) to predict the next
  word.
- Ships with a saved model (`next_word_lstm.h5`), a tokenizer, and a **Streamlit** app (`app.py`) for
  interactive prediction.
