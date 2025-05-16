
# 🤖 Hugging Face Web Chatbot

This project is a **console-based chatbot** that uses a Hugging Face language model to answer questions based on the content scraped from any public website.

---

## 📌 Features

- Scrapes website text using `requests` and `BeautifulSoup`
- Uses `google/flan-t5-base` model via `transformers.pipeline`
- Supports natural language Q&A about any URL's content
- Console-based interaction (type-to-chat)
- Handles Hugging Face model token limits safely

---

## 🔧 Requirements

Install dependencies before running:

```bash
pip install transformers requests beautifulsoup4
```

---

## 🚀 How to Run

1. Open in Jupyter Notebook or any Python IDE.
2. Run the script.
3. Enter a website URL when prompted (e.g. https://www.python.org/about/)
4. Ask questions based on the scraped content.
5. Type `'exit'` to quit the chatbot.

---

## 🧪 Example

```text
Enter the website URL: https://www.python.org/about/
✅ Website scraped successfully.

Ask something (type 'exit' to quit): What is Python?
Bot: Python is a popular programming language used for a wide range of applications.
```

---

## 💡 Model Notes

- **Model Used**: `google/flan-t5-base`
- Automatically cached locally at:
  ```
  C:/Users/<yourname>/.cache/huggingface/hub/
  ```

---

## 🧹 Cleaning Up

To free disk space, delete the cached model folder:
```
C:/Users/<yourname>/.cache/huggingface/hub/models--google--flan-t5-base
```

---

## 📚 References

- Hugging Face Transformers: https://huggingface.co/docs/transformers/index
- Model Card: https://huggingface.co/google/flan-t5-base
- BeautifulSoup Docs: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

---

## ✅ File Name Recommendation

You can name your script:
```bash
huggingface_web_chatbot.py
```

---

## ✍️ Author

Samad Zaidi
