# 🇬🇧🇹🇷 C2 English to Turkish Vocabulary Translator

This project is a simple and effective Python script that automatically translates C2 level (advanced) English words into Turkish using the Google Translate infrastructure and outputs the result in a clean **JSON** format.

## 🚀 Features
- Automatic translation of advanced English vocabulary.
- Stable and free Google Translate API connection using the `deep-translator` library.
- Includes `time.sleep()` between requests to avoid overloading the translation server (API limits/Best Practice).
- Outputs data in a structured dictionary format (JSON).

## 🛠️ Installation

To run the code on your local machine or Google Colab, you first need to install the required translation library:

```bash
pip install deep-translator
