# Buffett & Graham GPTs

**An AI investment advisor based on the philosophies of Warren Buffett and Benjamin Graham.**  
[View Buffett & Graham GPTs on ChatGPT](https://chatgpt.com/share/687059ff-86b4-8009-b71e-b9cd0c5fb70a)

---

## 📖 Overview

**Buffett & Graham GPTs** is a conversational AI investment advisor powered by the principles and theories of legendary investors Warren Buffett and Benjamin Graham.

- Designed for investors from beginners to advanced levels
- Provides engaging dialogue where Buffett and Graham discuss and explain topics together
- Offers both quantitative and qualitative analysis of investments
- Capable of summarizing investment news and performing individual stock analyses

Use it as a reference model for building investment-related content or developing AI tools for financial education.

---

## ✨ Key Features

- **Value Investing Explanations**
    - Covers content for beginner, intermediate, and advanced investors
    - Explains complex investment terms in simple language

- **Individual Stock Analysis**
    - Financial analysis (e.g. ROE, ROIC, FCF, equity ratio, etc.)
    - Displays 10-year historical data
    - Compares target companies with competitors
    - Qualitative insights on business models, brand strength, and management evaluation

- **Market News Commentary**
    - Summarizes news articles
    - Provides comments from the perspectives of both Buffett and Graham

- **Chart Analysis**
    - Generates stock price charts using matplotlib
    - Displays technical indicators (e.g. moving averages, RSI)
    - Performs scenario analysis for potential price movements (bull/bear cases)

- **Investment Content Generation**
    - Drafts articles, reports, and YouTube scripts

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

## 🚀 Usage Scenarios

This project is intended for various use cases, such as:

- Content generation for investment media platforms
- Building AI assistants for individual investors
- Automating individual stock analysis and news summaries
- Developing educational investment content

> ⚠ **Disclaimer**  
> This project does **not** constitute investment advice.  
> Always make your own investment decisions at your own risk.

---

## 🔧 Sample Code

Below is a simple example using the OpenAI API:

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

> “Invest like the legends — powered by AI.”


# バフェット＆グレアムGPTs

**ウォーレン・バフェットとベンジャミン・グレアムの投資哲学をもとに開発した投資アドバイザーAI**
https://chatgpt.com/share/687059ff-86b4-8009-b71e-b9cd0c5fb70a
---

## 📖 概要

「バフェット＆グレアムGPTs」は、  
ウォーレン・バフェットとベンジャミン・グレアムの投資理論をベースにした  
**対話型AI投資アドバイザー** です。

- 投資初心者から上級者まで幅広く対応
- バフェットとグレアムの掛け合い形式で解説
- 定量分析・定性分析の両面から投資情報を提供
- 投資ニュースの要約や個別株分析も可能

投資コンテンツ制作やAI活用の参考モデルとしてご活用ください。

---

## ✨ 主な機能

- **バリュー投資解説**  
    - 投資レベル別（初心者・中級・上級）対応
    - 難解な用語も平易に説明
- **個別株分析**
    - 財務分析（ROE、ROIC、FCF、自己資本比率 等）
    - 過去10年推移データの表示
    - 競合企業との比較
    - 定性分析（ビジネスモデル、ブランド力、経営者評価）
- **市況ニュース解説**
    - ニュースの要約
    - バフェットとグレアム、それぞれの視点でコメント
- **チャート分析**
    - 株価推移グラフ生成（matplotlib使用）
    - テクニカル指標表示（例：移動平均線、RSI 等）
    - 上昇シナリオ／下降シナリオのシナリオ分析
- **投資コンテンツ生成**
    - 記事、レポート、YouTube台本作成

---

## 🛠️ 技術スタック

- **言語・ライブラリ**
    - Python 3.x
    - pandas
    - matplotlib
    - OpenAI API (Chat Completion, Function Calling)
    - Markdown / HTML
- **アプリケーション例**
    - Streamlit / FastAPI
    - Jupyter Notebook（分析用）

---

## 🚀 Usage

本プロジェクトは主に以下のような用途を想定しています：

- 投資メディア運営者向けのコンテンツ生成
- 個人投資家向けAIアシスタント開発
- 個別株調査やニュース分析の自動化
- 投資教育コンテンツ制作

> ⚠ **注意**  
> 本プロジェクトは投資助言ではありません。  
> 実際の投資判断は必ずご自身の責任で行ってください。

---

## 🔧 サンプルコード

以下は、簡単な呼び出し例（OpenAI API）です：

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
