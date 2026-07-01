# 💱 Currency Converter with LangChain and Gradio

This project is a simple currency conversion demo built in a Jupyter notebook using LangChain, a Groq language model, and a Gradio interface. It shows how an LLM can use tools to fetch live exchange rates and calculate converted amounts.

## ✨ Features

- 💰 Converts between currencies using live exchange-rate data
- 🤖 Uses LangChain tool calling with a Groq model
- 🖥️ Provides an interactive Gradio web UI
- 🚀 Works well as a small demo or prototype for AI-powered finance applications

## ✅ Requirements

To run this project, you will need:

- 🐍 Python environment with Jupyter or Google Colab
- 🔑 A Groq API key
- 🌍 An Exchange Rate API key

## ⚙️ Setup

1. Open [Currency_Conv.ipynb](Currency_Conv.ipynb) in Jupyter or Google Colab.
2. Add your API keys as environment variables or Colab secrets:
   - `GROQ_API_KEY`
   - `EXCHANGE_RATE_API_KEY`
3. Run the notebook cells in order.

## 📦 Installation

The notebook installs the required packages automatically, but the main dependencies are:

```bash
pip install -q langchain-groq gradio
```

## ▶️ Usage

After running the notebook:

- 🤖 The LLM will use tools to fetch a conversion factor
- 🧮 The notebook will calculate the converted amount
- 🌐 A Gradio interface will launch so you can enter currencies and amounts interactively

## 📝 Notes

- 📌 The notebook currently uses Google Colab secret storage via `google.colab.userdata`.
- ⚠️ If you are running it outside Colab, set the API keys in your environment before executing the cells.

## 📁 Project Structure

- [Currency_Conv.ipynb](Currency_Conv.ipynb) – Main notebook containing the full workflow
- [README.md](README.md) – Project overview and usage instructions
