# PowerTrader AI 🚀
**Fully Automated Crypto Trading | Custom Pattern-Matching Intelligence | Smart DCA**

---

### What is this?
PowerTrader AI isn't your typical "black box" trading bot. It doesn't rely on vague indicators or over-hyped LLMs. 

Instead, it uses a **custom instance-based AI (kNN/kernel-style)** that works a lot like human intuition—but with a perfect memory.

**In simple terms:**
Imagine looking at a chart and saying, *"Hey, I've seen this exact pattern 50 times before. Usually, price goes up after this."* 
That is exactly what PowerTrader AI does, but it does it across **every single candle in history**, on **multiple timeframes** (1-hour up to 1-week), simultaneously.

It finds the closest historical matches to the current market action, checks what happened next in those past scenarios, and calculates a weighted probability for where the price is heading right now.

### How it Trades
The system is built on three core pillars to keep your portfolio moving:

1.  **Smart Entries**: The "Thinker" script constantly monitors the market. It only signals a buy if the price dips below the AI's predicted low on **at least 3 different timeframes** at once. This ensures we're buying on strong confluence, not random noise.
2.  **Protective DCA (Dollar Cost Averaging)**: If the market moves against a trade, the bot doesn't panic. It uses AI-derived support levels (or hard safety nets) to buy the dip.
    *   *Safety Feature:* Max 2 DCA buys per 24 hours to prevent "catching a falling knife" during crashes.
3.  **Trailing Profit Exits**: We don't just sell at a fixed target. We let winners run.
    *   **Standard Target:** 5% gain.
    *   **Recovery Target (after DCA):** 2.5% gain.
    *   **The Trail:** Once the target is hit, the bot activates a 0.5% trailing stop. It chases the price up until it reverses, squeezing out maximum profit.

---

### 📦 Setup Guide (Windows)
*Ready to run? Follow these steps exactly to get started.*

#### 1. Prerequisites
You need **Python** installed.
1.  Go to [python.org](https://www.python.org/downloads/).
2.  Download the latest version for Windows.
3.  **CRITICAL:** During installation, check the box that says **"Add Python to PATH"**.
4.  Click **Install Now**.

#### 2. Get the Code
*Note: Please download the files individually for now (we're fixing a quirk with the GitHub zip download).*

1.  Create a folder named `C:\PowerTraderAI` (or wherever you prefer).
2.  Save `pt_hub.py` and the other repo files into this folder.

#### 3. Install Dependencies
Open your **Command Prompt** (`Win` + `R`, type `cmd`, hit Enter) and run these commands:

```bash
cd C:\PowerTraderAI
```

If you are on Python 3.12+, run this first:
```bash
python -m pip install setuptools
```

Then install the bot requirements:
```bash
python -m pip install -r requirements.txt
```

#### 4. Launch the Hub
This is your mission control. You don't need to run separate scripts; the Hub manages everything.

```bash
python pt_hub.py
```

---

### ⚙️ Configuration & First Run

Once the PowerTrader Hub is open, head to **Settings**:

1.  **Main Neural Folder**: Point this to the folder where you saved the files (e.g., `C:\PowerTraderAI`).
2.  **Coins**: Select **BTC** to start.
3.  **Robinhood API Setup**:
    *   Click **Robinhood API Setup** inside Settings.
    *   Click **Generate Keys**. Copy the Public Key.
    *   Go to your Robinhood Crypto settings, add a new API key, and paste that Public Key.
    *   Enable **Trading** permissions when asked.
    *   Robinhood will give you an API Key (starts with `rh...`). Copy it.
    *   Paste it back into the bot's wizard and click **Save**.
4.  **Save Settings**.

*> Note: This creates `r_key.txt` and `r_secret.txt` locally. Never share these files!*

### 🧠 Training the Brain
Before it can trade, the AI needs to study the history.
1.  In the Hub, click **Train All**.
2.  Grab a coffee ☕. It will analyze the price history for your selected coins.

### 🚀 Start Trading
Once training is complete:
1.  Click **Start All**.
2.  The Hub will launch the `Thinker` (brain) and the `Trader` (execution).
3.  Sit back and monitor.

---

### Support the Project
PowerTrader AI is 100% free and open source. If this bot helps you make money, feel free to buy me a coffee (or a server)!

*   **Cash App:** $garagesteve
*   **PayPal:** @garagesteve
*   **Patreon:** patreon.com/MakingMadeEasy

### License
Released under the **Apache 2.0** License.
