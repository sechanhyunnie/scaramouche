# Daedalus

Daedalus is a discord bot built to pull and view CSS scores from servers running [Minos](https://github.com/sourque/minos). 

## Installation/Setup
To get started make sure to have a server with python 3 installed and a discord bot setup in the applications folder. You will need to change the server IP and bot token in the pub_bot.py file.
```python
# SPECIFY REMOTE HERE AND YOUR BOT TOKEN HERE
remote = '<SERVER ADDRESS HERE>'
bot_id = '<YOUR TOKEN HERE>'
# YOUR PREFIX
client = commands.Bot(command_prefix = '<YOUR PREFIX HERE>')
```
