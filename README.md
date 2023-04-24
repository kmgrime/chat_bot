# Chat Bot

[![Size](https://img.shields.io/github/languages/code-size/USERNAME/REPO_NAME)](https://github.com/kmgrime/chat_bot)
[![Downloads](https://img.shields.io/github/downloads/USERNAME/REPO_NAME/total)](https://github.com/kmgrime/chat_bot)
[![License](https://img.shields.io/github/license/kmgrime/chat_bot)](https://github.com/kmgrime/chat_bot/blob/main/LICENSE)

This is a simple chat bot written in Python. The bot loads a knowledge base from a JSON file, and then tries to find the best match to the user's question using the `difflib` library. If the bot finds a match, it returns the corresponding answer from the knowledge base. If it can't find a match, it prompts the user to provide an answer and adds it to the knowledge base.

## Getting Started

To use this chat bot, you need to have Python 3 installed on your system.

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies by running `pip install -r requirements.txt`.
4. Run the chat bot by running `python chat_bot.py`.
5. Type your question and hit enter.

## Usage

The chat bot will prompt you for a question. You can type any question you want, and the bot will try to find the best match in the knowledge base. If the bot finds a match, it will return the corresponding answer. If it can't find a match, it will prompt you to provide an answer, and then add it to the knowledge base for future use.

To quit the chat bot, type "quit" and hit enter.

## License

This project is licensed under the [GPL License](https://github.com/USERNAME/REPO_NAME/blob/main/LICENSE).
