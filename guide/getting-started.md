---
description: Let use this library!
---

# Getting started

## Before getting started...

We suggest you be familiar with `py-cord` and `python`. This is a `py-cord-components` guide so it couldn't contain a lot of python explanations.

## Install the library

First, we need to install the library:

```
pip install --upgrade py-cord-components
```

{% hint style="warning" %}
If you meet an error `No matching distribution found for py-cord-components` when installing, try updating the python version! (It must be upper than `3.6`)
{% endhint %}

## Send buttons

Assuming you have invited your bot to some server, let's code. Create any python file and copy & paste the code below. (with replacing `your token` with your bot's token and `your prefix` with your bot's prefix)

```
from py_cord_components import DiscordComponents, ComponentsBot, Button

bot = ComponentsBot(command_prefix = "your prefix")
"""
or you can just override the methods yourself

bot = discord.ext.commands.Bot("!")
DiscordComponents(bot)
"""


@bot.event
async def on_ready():
    print(f"Logged in as {bot.user}!")


@bot.command()
async def button(ctx):
    await ctx.send(
        "Hello, World!",
        components = [
            Button(label = "WOW button!", custom_id = "button1")
        ],
    )


bot.run("your token")
```
