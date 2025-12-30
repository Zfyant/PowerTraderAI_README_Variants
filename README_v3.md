<div align="center">

# 🤖 PowerTrader AI
### The Trading Bot That Thinks Like a Human (But Faster)

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)](https://github.com/yourusername/powertrader)

<br>

**Fully Automated Crypto Trading** • **Pattern-Matching Intelligence** • **Smart DCA**

[**Get Started**](#-quick-start-guide) • [**How It Works**](#-the-brain-knn-intelligence) • [**Support**](#-support-the-project)

<br>
<br>

</div>

---

## 🧠 The Brain: kNN Intelligence

<div align="center">
  <blockquote>
    "It works a lot like human intuition—but with a perfect memory."
  </blockquote>
</div>

<br>

Most bots use vague indicators. **PowerTrader AI** uses **Instance-Based Learning**. 

Imagine looking at a chart and saying:  
> *"Hey, I've seen this exact pattern 50 times before. Usually, price goes up after this."*

That is exactly what PowerTrader AI does. It scans **every single candle in history** across multiple timeframes (1H to 1W) to find the closest matches to the current moment. It then calculates a weighted probability of where the price is going next.

---

## ⚡ Core Features

<table align="center">
  <tr>
    <td align="center" width="33%">
      <h1>🎯</h1>
      <h3>Smart Entries</h3>
      <p>No random guessing. The <b>Thinker</b> script only signals a buy if the price dips below the AI's predicted low on <b>3+ timeframes simultaneously</b>. <br><br>We buy on <b>confluence</b>, not noise.</p>
    </td>
    <td align="center" width="33%">
      <h1>🛡️</h1>
      <h3>Protective DCA</h3>
      <p>Market dipped? Don't panic. The bot uses <b>AI-derived support levels</b> to buy the dip intelligently.<br><br><b>Safety First:</b> Max 2 DCA buys per 24h to prevent "catching a falling knife."</p>
    </td>
    <td align="center" width="33%">
      <h1>🚀</h1>
      <h3>Trailing Profits</h3>
      <p>We let winners run.<br><br><b>Target:</b> 5% Gain<br><b>Recovery:</b> 2.5% Gain<br><b>The Trail:</b> Once hit, a <b>0.5% trailing stop</b> chases the price up to squeeze every last drop of profit.</p>
    </td>
  </tr>
</table>

---

## 📦 Quick Start Guide

<div align="center">
  <h3>Ready to launch? Follow these steps.</h3>
</div>

<br>

### 1️⃣ Prerequisites
> **Python 3.10+ is required.**  
> [Download Python Here](https://www.python.org/downloads/)  
> ⚠️ **IMPORTANT:** Check the box **"Add Python to PATH"** during installation!

### 2️⃣ Installation

<details>
<summary><b>🔻 Click to expand Installation Instructions</b></summary>
<br>

1.  **Create a Folder**  
    Make a folder named `C:\PowerTraderAI`.

2.  **Download Files**  
    Download `pt_hub.py` and the repo files into that folder.

3.  **Install Dependencies**  
    Open Command Prompt (`cmd`) and run:
    ```bash
    cd C:\PowerTraderAI
    ```
    
    *If using Python 3.12+:*
    ```bash
    python -m pip install setuptools
    ```

    *Install Bot Requirements:*
    ```bash
    python -m pip install -r requirements.txt
    ```

</details>

### 3️⃣ Launch Control

<div align="center">

Just run one command to open the **PowerTrader Hub**:

```bash
python pt_hub.py
```

</div>

---

## ⚙️ Configuration Dashboard

Once the Hub is open, head to **Settings** to configure your bot.

| Setting | Action |
| :--- | :--- |
| **📂 Main Neural Folder** | Set to your install folder (e.g., `C:\PowerTraderAI`) |
| **🪙 Coins** | Select **BTC** to start (safest bet). |
| **🔑 Robinhood API** | 1. Click **Robinhood API Setup**.<br>2. Generate & Copy **Public Key**.<br>3. Add to Robinhood Crypto Settings.<br>4. Paste the **RH API Key** back into the bot.<br>5. **SAVE!** |

> **Note:** This creates `r_key.txt` and `r_secret.txt`. **Keep them safe!**

---

## 🚦 Usage Workflow

<div align="center">

<h3>STEP 1: 🧠 Train</h3>
Click <b>Train All</b> in the Hub.<br>
<i>The AI studies the entire price history. Grab a coffee ☕.</i>

⬇️

<h3>STEP 2: 🚀 Start</h3>
Click <b>Start All</b>.<br>
<i>The Hub launches the <b>Thinker</b> and <b>Trader</b> automatically.</i>

⬇️

<h3>STEP 3: 💰 Profit</h3>
<i>Sit back and monitor the trades.</i>

</div>

---

## ❤️ Support the Project

<div align="center">

**PowerTrader AI is 100% Free & Open Source.**  
*If this bot helps you make money, feel free to support the development!*

<a href="https://cash.app/$garagesteve">
  <img src="https://img.shields.io/badge/Cash_App-$garagesteve-00C244?style=for-the-badge&logo=cashapp&logoColor=white" alt="Cash App" />
</a>
<a href="https://paypal.me/garagesteve">
  <img src="https://img.shields.io/badge/PayPal-@garagesteve-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal" />
</a>
<a href="https://patreon.com/MakingMadeEasy">
  <img src="https://img.shields.io/badge/Patreon-Support_Us-F96854?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon" />
</a>

</div>

---

<div align="center">
  <sub>Released under the Apache 2.0 License.</sub>
</div>
