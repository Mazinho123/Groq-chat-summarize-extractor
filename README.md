# Groq Chat Summarizer & Info Extractor

This project implements:
1.  Chat history management with truncation and periodic summarization.
2.  User info extraction using OpenAI-compatible function calling (via Groq API).

## Task 1: Summarization
- Tracks all chat messages
- Supports truncation by number of turns or character count
- Performs summarization every k messages

## Task 2: Function Calling
- Extracts: name, email, phone, location, age
- Uses `llama-3.3-70b-versatile` for tool calling (Groq)
- Uses `llama-3.1-8b-instant` for summarization

## How to Run
1. Replace API key in `client = OpenAI(...)`
2. Run all cells in Google Colab
3. View printed outputs

**Author:** Devroop Dasgupta
