# 🧠 Markovify Text Generator

A Python project that uses Markov Chains to generate Shakespearean-style text using the `markovify` library and Project Gutenberg's Shakespeare corpus.

## 📌 Features

- Trains on Hamlet, Macbeth, and Julius Caesar
- Cleans and tokenizes text using spaCy + NLTK
- Generates both long and short sentences
- Easy to modify or train on custom text

## 🚀 How to Run

1. Install the dependencies:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
