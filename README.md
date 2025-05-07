# 🎉 Alfred the Party Planner — AI Code Agent with `smolagents`

This repository contains an AI agent — themed after **Alfred**, the iconic butler from Wayne Manor — who can help plan an epic party! Built using the [`smolagents`](https://github.com/smol-ai/smolagents) framework, this project demonstrates how to build a multi-step agent that reasons, generates code, uses tools, and executes dynamic solutions.

> 🦇 **Alfred** searches for music, suggests a menu, and calculates preparation time — making your party planning stress-free!

---

## 🚀 Features

* 🔍 **Music Recommendations** using DuckDuckGo Search
* 🍽️ **Menu Suggestions** (casual, formal, superhero-themed)
* 🕒 **Preparation Time Calculator** using Python code execution
* 🛠️ Powered by:

  * [smolagents](https://github.com/smol-ai/smolagents)
  * Hugging Face Inference API
  * Custom tools + dynamic code execution

---

## 🧠 How It Works

1. **Receives a party planning request**
2. **Breaks the request** into subtasks:

   * Find music 🎶
   * Suggest menu 🍕
   * Calculate prep time ⏰
3. **Generates & executes Python code** to compute solutions
4. **Combines results** into a structured plan ✅

---

## 📂 Project Structure

```
📦 alfred-party-planner-agent
 ┣ 📜 building-agent-that-uses-code.ipynb  # Main notebook
 ┣ 📜 README.md                            # Project README
 ┣ 📜 requirements.txt                    # Python dependencies
```

---
## 🛠️ Installation

1. **Clone this repository**

```bash
git clone https://github.com/OyewoleRasheed/AI-Code-Agent-with-smolagents.git
cd AI-Code-Agent-with-smolagents
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Launch the notebook**

```bash
jupyter notebook
```

---

## ✅ Requirements

* Python 3.8+
* Jupyter Notebook
* Hugging Face account (for Inference API)

Install Python packages:

```bash
pip install smolagents huggingface_hub
```

---

## 📊 Example Output

> **Alfred's Plan:**
>
> * Music: "Top 10 party anthems from DuckDuckGo search"
> * Menu: "Pizza, nachos, superhero cupcakes"
> * Prep Time: "3 hours and 45 minutes"

---

## 🌐 Learn More

* [smolagents GitHub](https://github.com/smol-ai/smolagents)
* [Hugging Face Agents Course](https://huggingface.co/agents-course)

---

## 📝 Credits

* Inspired by the [Hugging Face Agents Course — Unit 2](https://huggingface.co/agents-course/notebooks/blob/main/unit2/smolagents/code_agents.ipynb)
* Built using `smolagents` + Hugging Face models
* 🦇 Alfred the Butler spirit brought to AI party planning 🎉

---

## 🦇 Fun Fact

> "Master Wayne, the guests have been invited, the music selected, and the menu approved. Shall I prepare the Batcave as the dance floor?"
> — *Alfred, probably.*
