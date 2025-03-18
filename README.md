# ✨ YouTube Video Summarizer using LLM ✨

## 📖 Overview
This project is designed to extract and summarize YouTube videos efficiently using Large Language Models (LLMs). Since many AI models, including ChatGPT, cannot directly retrieve transcripts due to copyright restrictions, we implement a two-step approach to generate accurate summaries.

---

## ❓ Why Not Direct AI or ChatGPT for Summarization?
🔎 Many AI models do **not** directly summarize YouTube videos because they cannot access transcripts due to copyright policies.

Instead, our solution extracts the transcript separately and then processes it for summarization.

---

## 📚 Approach
1. ⭐ **Extracting Transcripts** - We use `youtube_transcript_api` to fetch the transcript from a given YouTube video.
2. ✅ **Formatting the Text** - The raw transcript is cleaned, punctuated, and structured for better readability.
3. 🤖 **Summarization using LLM** - The processed text is then sent to an LLM (ChatGPT Free Version) for generating a concise summary.

---

## 🛠️ How to Use
Follow these steps to test or use the summarizer:

1. ⬇ **Download the Jupyter Notebook (`.ipynb` file)** from this repository.
2. 📂 **Open it in Google Colab** (preferred for ease of use).
3. 🔐 **Replace your LLM API key** in the specified section.
4. 📹 **Provide the YouTube Video URL** you want to summarize.
5. ⏳ **Run all cells in the notebook.**
6. 🚀 *Boom!* The summary is generated instantly!

---

## 📦 Dependencies & Installation
Ensure you have the following installed:

```bash
pip install youtube_transcript_api openai
```

If using **Google Colab**, no additional setup is required except for providing your API key.

---

## 🌟 Features
- ✅ Automated transcript extraction
- ✅ Intelligent text formatting and punctuation
- ✅ Summarization using a free LLM model
- ✅ Easy-to-use Jupyter Notebook format

---

## 📢 Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

---

## 👀 Future Enhancements
- ⭐ Adding support for multiple LLMs.
- ⭐ Integrating with more platforms beyond YouTube.

---

💡 Happy Summarizing! 💡

