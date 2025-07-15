素晴らしいREADMEです！以下は **GitHubにそのまま貼り付けやすい形** に整えた最終版Markdownです。
表現を少しだけ自然にし、統一感を出しました。日本語部分も見出しレベルや改行などをGitHub向けに最適化しました👇

---

```markdown
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

# バフェット＆グレアムGPTs

> **「投資の伝説たちの知恵を、AIの力で。」**

---

## 📌 概要

**バフェット＆グレアムGPTs** は、ウォーレン・バフェットとベンジャミン・グレアムの投資哲学をベースにした **対話型AI投資アドバイザー** です。

「バフェット」と「グレアム」が掛け合い形式で投資の概念を解説し、個別株を定量・定性両面から分析、市況ニュースにもコメントします。
複雑な金融用語もわかりやすい日本語に言い換え、投資の理解をサポートします。

---

## ✨ 主な機能 / Key Features

✅ **バリュー投資解説**

* 初心者から上級者まで対応
* 難解な投資用語も平易に説明

---

✅ **個別株分析**

* 財務指標分析（ROE、ROIC、FCF、自己資本比率など）
* 過去10年分の財務データ表示
* 同業他社との比較
* ビジネスモデルやブランド、経営陣の定性評価

---

✅ **市況ニュース解説**

* 最新ニュースを要約
* バフェット＆グレアム視点のコメントを追加

---

✅ **チャート分析**

* matplotlibで株価チャートを生成
* テクニカル指標（移動平均線、RSIなど）の表示
* 上昇・下降シナリオ分析

---

✅ **投資コンテンツ生成**

* 記事、レポート、YouTubeスクリプトの作成

---

## 🎯 想定ユーザー / Target Users

* 個人投資家
* 金融教育やコンテンツ制作者
* 金融アプリ開発者
* 投資アドバイザーや金融業界の研究職

---

## 💻 使用例 / Usage Examples

以下のように入力するだけで、対話形式の投資アドバイスが得られます：

---

### 入力例

```
PERって何ですか？初心者向けに教えて。
```

---

### GPT の出力例

> **バフェット:** PER（株価収益率）は、株を買う人が企業の1円の利益にいくら払うかを示す指標だ。PERが高いのは成長期待が高い場合もあるけど、株価が割高な可能性もある。
>
> **グレアム:** その通りだ。PERは株の割安・割高を測る一つの目安だが、それだけでは不十分だ。利益の安定性や財務の健全さも必ず確認すべきだよ。

---

## 🛠️ 技術スタック / Tech Stack

* **言語・ライブラリ**

  * Python 3.x
  * pandas
  * matplotlib
  * OpenAI API (Chat Completion, Function Calling)
  * Markdown / HTML
* **アプリケーション例**

  * Streamlit / FastAPI
  * Jupyter Notebook（分析用途）

---

## 🚀 活用例 / Use Cases

* 投資教育コンテンツ制作
* 個人投資家向けAIアシスタント開発
* 個別株分析やニュース解説の自動化
* 金融リテラシー向上施策

> ⚠ **注意**
> 本ツールは投資助言を行うものではありません。
> 投資判断は必ずご自身の責任で行ってください。

---

## 🔧 サンプルコード / Sample Code

以下は OpenAI API を用いた簡単な呼び出し例です：

```python
from openai import OpenAI

client = OpenAI()

response = client.chat.completions.create(
    model="gpt-4",
    messages=[
        {"role":"system", "content":"あなたはバフェットとグレアムの投資アドバイザーです。"},
        {"role":"user", "content":"PERって何ですか？初心者向けに教えて。"}
    ]
)

print(response.choices[0].message.content)
```

---

## 👨‍💻 開発者 / My Role

本ツールでは以下を担当しました：

* バリュー投資分野に特化したプロンプト設計
* ユーザーが使いやすい対話設計
* 定量・定性分析のブラッシュアップ

---

## 📄 ライセンス / License

MIT License

---

> **「投資の伝説たちの知恵を、AIの力で。」**

```
