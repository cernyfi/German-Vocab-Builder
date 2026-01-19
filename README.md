# 🇩🇪 German Vocab Builder (AI-Powered)

**An intelligent vocabulary extraction tool for German learners.**

![App Screenshot](https://via.placeholder.com/800x400?text=App+Screenshot+Here)
*(Add a screenshot of your app here)*

The **German Vocab Builder** uses advanced AI to analyze German text files (books, subtitles, articles) and extract useful vocabulary based on your specific learning level. Unlike simple translators, it understands grammar rules—extracting singular nouns, infinitive verbs, and complete idiomatic phrases automatically.

> **Latest Version:** v3.5
> **Platform:** Windows 10/11

## 🚀 Key Features

* **Smart AI Extraction:** Filters out basic words (A1/A2) and focuses on what you actually need to learn (B2/C1, Business, or Slang).
* **Grammar Aware:** Automatically converts conjugated verbs to **Infinitives** (e.g., *ging* -> *gehen*) and nouns to **Singular/Nominative** (e.g., *Häuser* -> *das Haus*).
* **Contextual Translation:** Uses translation logic to provide accurate translations in your native language (English, Spanish, French, etc.).
* **Wiktionary Integration:** Fetches real grammatical gender (der/die/das) and verb forms using live data.
* **Multi-Model Support:** Works with **OpenAI (GPT-4o)**, **Google Gemini**, **Claude**, or **Local LLMs** (via LM Studio).

## 📥 Download

You can download the latest standalone version for Windows from the **Releases** page. No Python installation is required.

1.  Go to the **[Releases Page](../../releases)**.
2.  Download the `GermanVocabBuilder.exe`.
3.  Double-click to run.

## 🛠️ How to Use

1.  **API Setup:**
    * Choose your AI Provider (Gemini is recommended for free/fast usage).
    * Enter your API Key.
    * Enter your email (required for Wiktionary data attribution).

2.  **Configuration:**
    * **Target Language:** Enter the 2-letter code for your native language (e.g., `en` for English, `es` for Spanish, `fr` for French).
    * **Input Folder:** Select the folder containing your German `.txt` or `.srt` (subtitle) files.
    * **Output Folder:** Choose where to save the resulting CSV file.

3.  **Select a Preset:**
    * Choose a preset like **"Advanced (B2/C1)"** or **"Slang & Colloquial"**.
    * *Optional:* You can edit the system prompt manually for custom needs.

4.  **Start:**
    * Click **START**. The app will process your files in chunks of ~600 words.
    * You can **PAUSE** and **RESUME** at any time.

## ⚙️ Supported AI Models

* **Google Gemini:** (Recommended for speed & cost)
* **OpenAI:** GPT-4o / GPT-3.5
* **Anthropic Claude:** Via OpenRouter
* **Local LLMs:** Any model running on LM Studio (e.g., Llama 3, Mistral)

## 📄 License & Attribution

* **Grammar Data:** Sourced from [Wiktionary](https://de.wiktionary.org/) under the **CC BY-SA 3.0** license.
* **Software License:** MIT License. Free for personal and educational use.

---

*Created by Filip Černý, 2025*