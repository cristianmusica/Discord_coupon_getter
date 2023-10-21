**About:**

Un codigo modificado de https://github.com/irrinata/Udemy_coupon_scrape el codigo del actual repositorio es para bot de discord, el repositorio anteriormente proporcionado, es para bots de telegram que lo redirigen a un canal de telegram.
To prevent sending same coupon twice it adds all new records into a database and stores them for a month.

**Usage: main.py token chat**

You will need your own token and channel or chat to run it.

    positional arguments:
    token   discord bot token
    chat    discord channel id

**Requirements:**

requests
beautifulsoup4
pyTelegramBotAPI
lxml
