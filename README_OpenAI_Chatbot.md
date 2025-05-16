
# 🤖 OpenAI Web Chatbot (Console-Based)

This project is a **console chatbot** that uses the **OpenAI GPT-3.5-Turbo API** to answer user questions based on the content scraped from a given website URL.

---

## 📌 Features

- Scrapes website text using `requests` and `BeautifulSoup`
- Uses OpenAI GPT-3.5 model to answer questions
- Works entirely from the console (no frontend)
- Supports real-time interaction with scraped context

---

## 🔧 Requirements

Install the necessary Python packages:

```bash
pip install openai requests beautifulsoup4
```

---

## 🚀 How to Run

1. Replace `"sk-abcdef1234567890abcdef1234567890abcdef12"` with your actual [OpenAI API key](https://platform.openai.com/account/api-keys).
2. Run the script in Jupyter or any Python terminal.
3. Enter a URL when prompted (e.g., https://www.python.org/about/).
4. Ask questions based on the page’s content.
5. Type `'exit'` to quit the chat session.

---

## 🧪 Example Interaction

```text
Enter the website URL: https://www.python.org/about/
✅ Website scraped successfully.

Ask something (type 'exit' to quit): What is Python?
Bot: Python is a powerful programming language that is easy to learn and used in various fields like web development, data science, and automation.
```

---

## 🔐 Security Note

Never share or hard-code your OpenAI API key in public repositories. Always keep it in an environment variable or a secrets manager for production use.

---

## 💡 Limitations

- Works best on websites with clean `<p>` text content.
- Limited to ~3500 characters of website content due to token constraints.
- Requires active internet connection and valid API key.

---

## ✅ File Name Suggestion

```bash
openai_web_chatbot.py
```

---

## ✍️ Author

Samad Zaidi
