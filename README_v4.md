# 🚀 PowerTrader_AI

<div align="center">

### Automated crypto trading that learns from history and trades on pattern recognition.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)
![Python](https://img.shields.io/badge/python-3.8+-yellow.svg)

[🎯 Features](#-what-makes-this-different) • [📚 How It Works](#-how-it-actually-trades) • [⚡ Quick Start](#-getting-started) • [💰 Support](#-support-the-project)

</div>

---

## 🎯 What Makes This Different?

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  Most AI Trading Bots          PowerTrader_AI              │
│  ═══════════════════          ═══════════════               │
│                                                             │
│  🧠 Complex Neural Networks    📊 Pattern Recognition       │
│  ❓ Black Box Decisions        ✅ Transparent Logic         │
│  💸 Expensive GPU Training     💻 Runs on Any Computer      │
│  🎲 Unpredictable Results      📈 Learn from History        │
└─────────────────────────────────────────────────────────────┘
```

</div>

When most people hear "AI trading bot," they picture complex neural networks or ChatGPT-style models. **PowerTrader_AI takes a completely different approach**—one that's surprisingly straightforward yet powerful.

### 🔍 Think of it like this:

<table>
<tr>
<td width="50%">

#### 📖 The Learning Phase
The system studies **every price pattern** in a coin's entire trading history—like building a massive encyclopedia of "what happened when."

</td>
<td width="50%">

#### 🎯 The Prediction Phase
When it sees a pattern forming **right now**, it looks back at similar patterns and asks: *"What happened next in those situations?"*

</td>
</tr>
</table>

<div align="center">

### ⏱️ Multi-Timeframe Intelligence

| Timeframe | What It Sees |
|-----------|--------------|
| 📅 **1 Hour** | Short-term momentum shifts |
| 📊 **4 Hours** | Intraday trend changes |
| 📈 **1 Day** | Daily market cycles |
| 📆 **1 Week** | Major trend reversals |

</div>

The best part? **The system learns from its mistakes.** After each candle closes, it checks its predictions against reality and adjusts the reliability scores for the patterns it used. Over time, it gets better at knowing which historical patterns are actually useful.

> 💡 **It's beautifully simple, and yes—it absolutely counts as AI.**

---

## 🎮 How It Actually Trades

<div align="center">

### Three-Stage Smart Trading System

</div>

### 🎯 Stage 1: Starting a Trade

<div align="center">

```
Price crosses 3+ predicted lines → 🚨 OVERSOLD SIGNAL → 💰 BUY
```

</div>

The system watches for moments when the current price drops below **at least 3 of its predicted low-price lines** across different timeframes. This is its way of saying:

> "Multiple timeframes agree this is oversold—time to buy." 🎯

---

### 📊 Stage 2: Dollar-Cost Averaging (DCA)

<div align="center">

| DCA Trigger | Action | Safety Limit |
|-------------|--------|--------------|
| 🔵 Cross 4th line | Add to position | ⚠️ Max 2 DCAs |
| 🔵 Cross 5th line | Add to position | per 24hrs |
| 📉 Drawdown % hit | Add to position | to prevent overtrading |

</div>

After entering a position, the bot uses a **tiered DCA system** to manage risk. There's a safety mechanism built in: **maximum 2 DCAs within any rolling 24-hour window.** This prevents you from emptying your entire account during an extended downtrend.

---

### 💎 Stage 3: Taking Profits (Trailing System)

<div align="center">

```
┌──────────────────────────────────────────────────────┐
│  No DCA Trade:  5.0% profit target  🎯               │
│  With DCA:      2.5% profit target  🎯               │
│  Trail Gap:     0.5% buffer        📈                │
│                                                       │
│  Price rises → Profit line rises with it! 🚀        │
│  Price drops → Lock in those gains! 💰              │
└──────────────────────────────────────────────────────┘
```

</div>

The trailing mechanism has a **0.5% gap**, meaning once price climbs 0.5% above your profit target, the target line starts rising with it. This lets you **capture bigger moves** while protecting against giving back too much if the price reverses.

---

## ⚡ Getting Started

<div align="center">

### ⚠️ READ THIS FIRST ⚠️

**This software places REAL trades with REAL money.**

You're the captain of this ship. Keep your API keys secure, understand what you're doing before you start, and never risk more than you can afford to lose.

🚫 We're not financial advisors • ✅ This is a tool • 💪 How you use it is entirely on you

---

### 📋 Pre-Flight Checklist

</div>

- [ ] If you hold crypto in Robinhood, **transfer it out or sell to cash first**
- [ ] Have Windows Command Prompt ready
- [ ] 30 minutes of setup time
- [ ] Coffee ☕ (optional but recommended)

---

### 1️⃣ Install Python

<div align="center">

```bash
🐍 Head to python.org → Download Windows installer → Run it
```

**⚠️ CRITICAL:** Check "Add Python to PATH" during installation!

</div>

---

### 2️⃣ Download PowerTrader_AI

<div align="center">

⚠️ **DON'T use the "Download ZIP" button** (there's a bug to fix)

</div>

**Instead, do this:**

1. 📁 Create a folder: `C:\PowerTraderAI\`
2. 🔗 Go to the PowerTrader_AI GitHub page
3. 🖱️ Right-click `pt_hub.py` → "Save Link As..." → save to your folder
4. 🔁 Repeat for **every file** in the repo (skip README and LICENSE)

---

### 3️⃣ Install Dependencies

<div align="center">

```bash
# Open Command Prompt (Windows key → type 'cmd' → Enter)

cd C:\PowerTraderAI

# If using Python 3.12+, run this first:
python -m pip install setuptools

# Install everything PowerTrader_AI needs:
python -m pip install -r requirements.txt
```

</div>

---

### 4️⃣ Launch the Hub 🎛️

<div align="center">

```bash
python pt_hub.py
```

**The PowerTrader Hub will open—this is your command center!** 🚀

</div>

---

### 5️⃣ Configure Your Setup ⚙️

<div align="center">

### Open **Settings** and follow these in order:

</div>

<table>
<tr>
<td width="33%">

#### 📂 Set Directory
Point "Main Neural Folder" to your `pt_hub.py` location

</td>
<td width="33%">

#### 🪙 Choose Coins
Start with **BTC** only while learning

</td>
<td width="33%">

#### 🔑 Connect Robinhood
Follow the API wizard carefully

</td>
</tr>
</table>

---

#### 🔐 Robinhood API Setup (Step-by-Step)

<div align="center">

```
1. Click "Generate Keys" in wizard
2. Copy the Public Key
3. Add API key in Robinhood → paste Public Key
4. Enable trading permissions
5. Copy Robinhood's API Key (starts with 'rh')
6. Paste back into wizard → Save
7. Close wizard → Save Settings
```

**You'll get:** `r_key.txt` and `r_secret.txt` 🔒  
**Guard these files with your life!**

</div>

---

### 6️⃣ Train the System 🧠

<div align="center">

The system needs to build its pattern memory before it can trade.

```
Click "Train All" → Grab coffee ☕ → Wait for completion
```

*First training takes a while—the system is studying the entire price history!*

</div>

---

### 7️⃣ Go Live! 🚀

<div align="center">

```
Click "Start All"
```

The Hub handles everything automatically:
- ✅ Launches `pt_thinker.py` first
- ✅ Waits for it to get ready  
- ✅ Starts `pt_trader.py`
- ✅ You don't need to juggle multiple programs!

**You're now officially trading with AI.** 🎉

</div>

---

## 📊 Understanding Neural Levels

<div align="center">

### The Signal Dashboard

| Signal | Meaning | Action |
|--------|---------|--------|
| 🟢 **LONG 0-2** | Weak buy signal | Wait |
| 🟢 **LONG 3+** | Strong buy signal | Ready to trade |
| 🔴 **SHORT 0** | No sell pressure | Clear to buy |
| 🔴 **SHORT 1+** | Sell pressure detected | Don't enter |

### 🎯 The Magic Combination

```
LONG 3+ AND SHORT 0 = 🚀 TRADE STARTS
```

This means multiple timeframes are screaming "oversold" with no opposing sell pressure!

</div>

---

## ➕ Adding More Coins Later

<div align="center">

**Once you're comfortable, expand your portfolio:**

```
Settings → Add coin → Save → Train All → Start All
```

*Start with 1-2 coins, don't go crazy! 🎯*

</div>

---

## 💰 Support the Project

<div align="center">

### PowerTrader_AI is completely **FREE** and **open source**! 🎉

If it makes you money and you want to say thanks:

[![Cash App](https://img.shields.io/badge/Cash%20App-$garagesteve-00C244?style=for-the-badge&logo=cash-app&logoColor=white)](https://cash.app/$garagesteve)
[![PayPal](https://img.shields.io/badge/PayPal-@garagesteve-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/garagesteve)
[![Patreon](https://img.shields.io/badge/Patreon-MakingMadeEasy-FF424D?style=for-the-badge&logo=patreon&logoColor=white)](https://patreon.com/MakingMadeEasy)

Every bit helps keep development going! ❤️

</div>

---

## 📜 License

<div align="center">

Released under the **Apache 2.0** license

**Use it • Modify it • Share it** 🚀

---

**Made with** ❤️ **by garage coders, for garage coders**

</div>