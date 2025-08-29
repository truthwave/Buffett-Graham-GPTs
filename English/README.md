<p align="center">
<img width="1536" height="1024" alt="投資の伝説たちの知恵を、AIの力で。" src="https://github.com/user-attachments/assets/fcca5568-451f-4a23-8da7-8f12697dfa62" />
</p>

# Buffett & Graham GPTs

> **“Invest like the legends — powered by AI.”**

---

## 📌 Overview

**Buffett & Graham GPTs** is a conversational AI investment assistant inspired by the timeless principles of Warren Buffett and Benjamin Graham.

This tool generates engaging dialogues in which “Buffett” and “Graham” discuss investing concepts, analyze individual stocks both quantitatively and qualitatively, and comment on market news—all while simplifying complex financial ideas into language that’s easy to understand.

It’s ideal for:

- Individual investors seeking educational tools
- Content creators producing investment-related articles, videos, or blogs
- Developers building financial education apps
- Professionals needing inspiration for investment analysis reports

---

## ✨ Key Features

✅ **Value Investing Explanations**

- Covers topics for beginner, intermediate, and advanced investors
- Explains complex financial concepts in plain language

---

✅ **Individual Stock Analysis**

- Calculates financial metrics (e.g. ROE, ROIC, FCF, equity ratio)
- Displays historical financial data (10-year trends)
- Compares companies against competitors
- Provides qualitative insights on business models, brands, and management teams

---

✅ **Market News Commentary**

- Summarizes recent market news
- Adds commentary from both Buffett’s and Graham’s perspectives

---

✅ **Chart Analysis**

- Generates price charts with matplotlib
- Shows technical indicators (moving averages, RSI, etc.)
- Performs scenario analyses for potential price movements

---

✅ **Investment Content Generation**

- Drafts investment articles, reports, or video scripts

---

## 🎯 Target Users

- Individual investors
- Financial educators and content creators
- Developers of financial apps
- Investment advisors looking for research support

---

## 💻 Usage Examples

Here’s how you might use Buffett & Graham GPTs:

---

### Example Prompt

```

What is the P/E ratio? Explain it for beginners.

````

---

### GPT Example Output

> **Buffett:** The P/E ratio tells you how much investors are paying for $1 of a company’s earnings. A high P/E might mean people expect growth, but it could also mean the stock is expensive.  
>  
> **Graham:** Exactly. The P/E ratio helps assess valuation. However, it’s just one tool—you must also look at earnings stability and financial strength.

---

## 🛠️ Tech Stack

- **Languages & Libraries**
  - Python 3.x
  - pandas
  - matplotlib
  - OpenAI API (Chat Completion, Function Calling)
  - Markdown / HTML
- **Example Application Frameworks**
  - Streamlit / FastAPI
  - Jupyter Notebook for analysis

---

## 🚀 Use Cases

- Creating educational investment content
- Building AI investment assistant apps
- Automating stock analysis and news summaries
- Supporting financial literacy initiatives

> ⚠ **Disclaimer**  
> This tool does **not** constitute investment advice.  
> Always conduct your own due diligence and make investment decisions at your own risk.

---

## 🔧 Sample Code

A simple example using the OpenAI API:

```python
from openai import OpenAI

client = OpenAI()

response = client.chat.completions.create(
    model="gpt-4",
    messages=[
        {"role":"system", "content":"You are an investment advisor speaking as Buffett and Graham."},
        {"role":"user", "content":"What is the P/E ratio? Explain it for beginners."}
    ]
)

print(response.choices[0].message.content)
````

---

## 👨‍💻 My Role

I developed this GPT, handling:

* Prompt engineering tailored to value investing topics
* User experience design for clear dialogue outputs
* Refinement of both quantitative and qualitative investment analysis explanations

---

## 📄 License

MIT License

---

---
