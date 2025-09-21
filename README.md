# GAFA株価可視化アプリ / GAFA Stock Price Visualization App

![My Image](image/demo.gif)


## 📘 概要 - Overview

**日本語**  
本アプリは、米国の主要IT企業（GAFA：Google, Apple, Facebook, Amazon）の株価変動をグラフ形式で可視化するツールです。
Streamlit を使って、簡単に Web ブラウザで動作します。

**English**  
This application is a tool for visualizing stock price movements of major US IT companies (GAFA: Google, Apple, Facebook, Amazon) in graph format.
It runs easily in a web browser using Streamlit.

---

## 🛠️ 事前準備 - Installation

**日本語**  
以下の手順でアプリを実行できます：

1. Python 環境が整っていることを確認してください。
2. Streamlit をインストールします：

**English**  
You can run the app by following these steps:

1. Make sure you have a Python environment set up.
2. Install Streamlit:

```bash
pip install streamlit
```

---

## 🚀 実行方法 - How to Run

**日本語**  
メインファイル `app.py` を使用します。
以下のコマンドでアプリを起動してください：

**English**  
Use the main file `app.py`.
Start the app with the following command:

```bash
streamlit run app.py
```

**日本語**  
起動後、ブラウザでアプリが開き、GAFAの株価が表示されます。

**English**  
After startup, the app will open in your browser and display GAFA stock prices.

---

## ⛔ Streamlitの終了方法 - How to Stop Streamlit

**日本語**  
▶️ ターミナル・コマンドラインで起動した場合（`streamlit run app.py`）

**English**  
▶️ When started from terminal/command line (`streamlit run app.py`)

### ⏰ 終了方法 - How to Stop:

**日本語**  
ターミナルで **Ctrl + C** を押すだけです！

**English**  
Simply press **Ctrl + C** in the terminal!

* **Mac / Linux**: `Control + C`
* **Windows**: `Ctrl + C`

**日本語**  
これでStreamlitサーバーが停止し、アプリが終了します。

**English**  
This will stop the Streamlit server and terminate the app.

### 🧹 念のためキャッシュもクリアしたい場合 - If you want to clear cache as well (Optional)

```bash
streamlit cache clear
```

### 📍 VSCodeターミナルを使っている場合 - When using VSCode terminal

**日本語**  
ターミナルを止める方法は以下のいずれかです：

**English**  
You can stop the terminal using either of the following methods:

* `Ctrl + C`
* **日本語**: ターミナルパネルの右上にある「ゴミ箱アイコン」（終了）をクリック
* **English**: Click the "Trash icon" (terminate) in the upper right corner of the terminal panel

---

## 📄 補足 - Notes

**日本語**  
* 本アプリはデモ目的であり、実際の投資判断には利用しないでください。
* GAFAの株価情報は外部APIまたはCSVファイルを利用して取得している場合があります。

**English**  
* This app is for demonstration purposes only and should not be used for actual investment decisions.
* GAFA stock price information may be obtained using external APIs or CSV files.
---
