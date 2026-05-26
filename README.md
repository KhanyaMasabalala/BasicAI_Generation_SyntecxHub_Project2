# Syntecxhub_Simple_Rule-Based_Chatbot

## 📌 Project Overview
[cite_start]This repository contains **AI Assist**, an interactive, rule-based desktop chatbot application developed as part of the Week 2 Task for the Syntecxhub Artificial Intelligence Internship program[cite: 15, 27, 28]. 

The application is built entirely in Python and provides a clean Graphical User Interface (GUI) alongside a pattern-matching conversational engine and an arithmetic parser to handle basic mathematical operations.

## 🚀 Key Features
* **Interactive GUI Layout:** Built with `tkinter` using a scrollable text area (`ScrolledText`) to display the live dialogue history dynamically.
* [cite_start]**Basic Arithmetic Engine:** Automatically detects and extracts numbers from natural language to compute operations like addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`)[cite: 30].
* **Background Threading Engine:** Runs the rule-matching processor on a separate, background daemon thread, ensuring the desktop application never freezes or becomes unresponsive during computation.
* [cite_start]**Persistent Conversation History Logging:** Automatically logs and appends every interaction with an exact date and timestamp to a local text file (`chat_history_log.txt`).

## 🛠️ Technical Requirements & Libraries
The project uses standard, built-in Python 3 libraries, meaning no external dependencies or `pip` installations are required:
* `tkinter` & `scrolledtext` — For rendering the desktop window user interface.
* `re` — For regular expression pattern matching and extracting variables.
* `threading` — For managing asynchronous execution tasks in the background.
* `datetime` — For generating timestamps for persistent data logging.

## 💻 How to Run the Application
1. Clone this repository to your local computer:
   ```bash
   git clone [https://github.com/samaladyasa/Syntecxhub_Simple_Rule-Based_Chatbot.git](https://github.com/samaladyasa/Syntecxhub_Simple_Rule-Based_Chatbot.git)
