# 🤖 CodeAlpha Basic Chatbot

A simple **rule-based chatbot built using Python** that simulates a basic conversational interface. This beginner-friendly project demonstrates fundamental Python concepts such as string matching, conditional statements, loops, user input handling, and randomized responses.

The chatbot interacts with users through the console, responds to common conversational phrases, and continues the conversation until the user types `bye`.

## 📌 Features

- 🗨️ **Greeting Recognition:** Responds to greetings such as `hi`, `hello`, and `hey`.
- 😊 **Basic Conversations:** Replies to phrases such as `how are you`.
- 👤 **Name Recognition:** Recognizes name introductions like `my name is Sania`.
- 🔄 **Randomized Responses:** Uses Python's `random` module to provide varied replies.
- ❌ **Exit Handling:** Ends the conversation when the user types `bye`.
- 💬 **Fallback Responses:** Provides a default reply when the input is not recognized.
- 🖥️ **Console Interface:** Offers a simple, interactive text-based chatting experience.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Module:** `random` (Python standard library)
- **Interface:** Command-line / Console
- **Dependencies:** No external libraries required.

## ⚙️ How It Works

1. The chatbot displays a welcome message.
2. The user enters a message through the console.
3. The program processes the input and matches it against predefined words or phrases.
4. Based on the input, the chatbot selects an appropriate response.
5. The `random` module varies responses where applicable.
6. The conversation continues until the user types `bye`.

## 🚀 Getting Started

### Prerequisites

Make sure Python 3 is installed on your system.

Check your Python installation:

```bash
python --version
```

Alternatively, on some systems, use:

```bash
python3 --version
```

### Installation

**1. Clone the repository**

```bash
git clone <your-repository-url>
```

**2. Navigate to the project directory**

```bash
cd codealpha_basic_chatbot
```

**3. Run the chatbot**

```bash
python chatbot.py
```

If your source file has a different name, replace `chatbot.py` with the actual filename.

## 💻 Example Conversation

```text
Bot: Hi! I'm ChatBot. Type 'bye' to end the chat.

You: hi
Bot: Hello! 👋

You: how are you
Bot: I'm good, thanks! 😎

You: my name is Sania
Bot: Nice to meet you, Sania!

You: bye
Bot: Bye! Have a great day 👋
```

*Note: The exact responses may vary depending on the implementation and randomized reply selection.*

## 📂 Project Structure

```text
codealpha_basic_chatbot/
│
├── chatbot.py
└── README.md
```

*Note: The filename `chatbot.py` is an example. Update the project structure to match your actual files.*

## 🧠 Python Concepts Demonstrated

- Variables and data types
- Strings and string manipulation
- Conditional statements (`if`, `elif`, `else`)
- Loops (`while`)
- User input and output (`input()`, `print()`)
- Lists and randomized selection using `random`
- Basic text matching and pattern recognition
- Functions and program control flow

## 🎯 Project Objective

The objective of this project is to develop a basic conversational chatbot while learning Python fundamentals. It demonstrates how predefined rules and string matching can be used to recognize user messages and generate appropriate responses.

## 🔮 Future Improvements

- Add more conversational patterns and responses.
- Improve message matching using regular expressions.
- Add a graphical user interface (GUI).
- Store conversation history.
- Integrate natural language processing (NLP) for more flexible conversations.

## 👩‍💻 Internship Details

- **Organization:** CodeAlpha
- **Project:** Basic Chatbot
- **Technology:** Python 3
- **Project Type:** Beginner-level rule-based chatbot

---

⭐ If you find this project interesting, consider giving the repository a star!

