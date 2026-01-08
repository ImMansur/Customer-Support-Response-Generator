---

# 🎧 Customer Support Response Generator

A simple Python-based application that generates **professional customer support responses** using Azure OpenAI, with support for multiple support domains through external prompt templates.

---

## 🚀 Features

Generate customer support responses using Azure OpenAI

Supports multiple support domains:

General Support
Technical Support
Billing Support

Prompt templates stored as `.txt` files

Easy to extend with new support domains

Environment-variable based configuration

---

## 🛠️ Setup

```bash
git clone https://github.com/ImMansur/Customer-Support-Response-Generator.git
cd Customer-Support-Response-Generator
pip install -r requirements.txt
```

---

## 🔐 Environment Variables

Create a `.env` file in the project root:

```env
AZURE_OPENAI_API_KEY=your_api_key_here
AZURE_OPENAI_ENDPOINT=https://your-resource-name.openai.azure.com/
AZURE_OPENAI_DEPLOYMENT=your-deployment-name
```

---

## ▶️ Run

```bash
python src/app.py
```

You’ll be prompted to select a support domain:

Available options: General Support, Technical Support, Billing Support

Select option:

---

## ✏️ Customization

Change Product Name
Edit in `app.py`:

```python
{"product_name": "Smart Fitness Watch"}
```

Add a New Support Domain
Add a new prompt file in `prompts/`
Register it in the menu inside `app.py`

---

## 🌐 API Used

Azure OpenAI

---

## 📂 Storage

Prompt templates are stored in:

```text
prompts/
```

---

## 👤 Author

Mansur
GitHub: [https://github.com/ImMansur](https://github.com/ImMansur)

---

