# Anonymous-chat-telegram
Bot uses several libraries:
* [TeleBot](https://github.com/eternnoir/pyTelegramBotAPI) - API Telegram for python
* [SQLAlchemy](http://www.sqlalchemy.org) - Interaction with the database

You can install libraries with pip:
```sh
$ pip install pyTelegramBotAPI
$ pip install SQLAlchemy
```

_BinaryTree.py_ contains a binary search tree for fast searching users in list. You can use this class in your project, 
because tree node contains the key and the appropriate object.

The basis of the bot is _ChatBot.py_. To start the bot you need to get token for your bot. To create bot you can with **@BotFather** in telegram.