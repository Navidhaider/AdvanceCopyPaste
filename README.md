# Advance Copy Paste Automation 🚀

A lightweight Python script designed to eliminate the friction of repetitive data entry. 

Instead of constantly switching windows to copy and paste lines from a text document one by one, this tool reads your entire document in the background. Simply press the **Insert** key, and the script will automatically paste the next line from your list directly into your active window and hit Enter.

Perfect for filling out forms, migrating lists, or automating repetitive messaging.

## ✨ Features
* **Sequential Pasting:** Reads a text file and pastes it line-by-line sequentially.
* **Global Hotkey:** Works in the background across any application using the `Insert` key.
* **Auto-Submit:** Automatically simulates the `Enter` key after pasting.
* **Quick Exit:** Instantly terminate the script anytime by pressing `q`.

---

## 🛠️ Complete Setup Guide (For Beginners)

### Step 1: Install Python
1. Go to the official Python website: [python.org/downloads](https://www.python.org/downloads/)
2. Download the latest version for your operating system.
3. **CRITICAL:** When running the installer, you **must** check the box at the bottom that says **"Add Python to PATH"** before clicking Install.

### Step 2: Download This Tool
1. Click the green **Code** button at the top of this repository and select **Download ZIP**.
2. Extract the folder to your computer (e.g., your Desktop or a dedicated Scripts folder).

### Step 3: Install Required Libraries
This script relies on two external libraries to control your keyboard and clipboard.
1. Open your computer's terminal (Command Prompt on Windows, Terminal on Mac).
2. Run the following command:
   ```bash
   pip install keyboard pyperclip
