---
description: Before asking a question, look at these :)
---

# Frequently Asked Questions

Before, check you are using the correct library (`py-cord-components` not `pycord-components`) and if your library is in [the newest version](https://pypi.org/project/py-cord-components).

## How to make buttons inline?

Your code must be something like

```python
await <discord.abc.Messageable>.send(
    ...,
    components = [
        Button(...),
        Button(...),
        Button(...)
    ]
)
```

You should use a two-dimensional array like below to make buttons inline.

```python
await <discord.abc.Messageable>.send(
    ...,
    components = [
        [
            Button(...),
            Button(...),
            Button(...)
        ]
    ]
)
```

## How do I remove components?

Simple. Edit the message with parameter `components` set to `[]`.

```python
msg = await <discord.abc.Messageable>.send(
    ...,
    components = [...]
)
interaction = await <discord.ext.commands.Bot or discord.Client>.wait_for("event")

# First option
await msg.edit(components = [])
# Second option
await interaction.edit_origin(
    components = []
)
```

## How do I ignore the interaction?

Just respond with the type `6` with no other parameters or defer with edit\_origin enabled.

## Global event

There is an event `on_button_click` and `on_select_option`. You can use this as normal events.

```python
@<discord.ext.commands.Bot or discord.Client>.event
async def on_button_click(interaction):
    if interaction.responded:
        return
    await interaction.send(content = "Yay!")

@<discord.ext.commands.Bot or discord.Client>.event
async def on_select_option(interaction):
    if interaction.responded:
        return
    await interaction.send(content = "Yay!")
```

There is [an example using cogs](https://github.com/spacedev-official/py-cord-components/blob/dev/examples/cog.py) on GitHub.

## TypeError: send() got an unexpected keyword argument 'components'

Have you put `PycordComponents(<discord.Client or discord.ext.commands.Bot>)` inside the `on_ready` event or initialized the bot with `ComponentsBot`?

## Handle multiple interacts

You should put a while on `discord.Client.wait_for` to handle multiple clicks

```python
while True:
    interaction = await <discord.ext.commands.Bot or discord.Client>.wait_for("event")
    await interaction.send(content = "Wow")
```

## Disabling the components for specific users

This is impossible but you can ignore the interaction by putting a check.

```python
interaction = await <discord.ext.commands.Bot or discord.Client>.wait_for(
    "event",
    check = lambda i: i.user.id == "something"
)
```

## **I get ''404 Not Found (error code: 10062): Unknown interaction''**

Check if you already responded to the interaction.

## Using custom emoji

You send a `discord.Emoji` object to the parameter. You can get the custom emoji by doing

```python
<discord.ext.commands.Bot or discord.Client>.get_emoji(849325102746042439)
```

## **Can I set my own colors for buttons?**

No. Try reading [this](https://github.com/discord/discord-api-docs/issues/3022).
