# Forceful Unworry (Discord)
> 😔 Discord continuously makes me worried, nervous and has ruined my attention span.

## What is this?

This will remove certain features from Discord such as:

- `...is typing`
- `is playing...`
- Player status

## Why...?

All of those things have eaten my attention span and now I'm left with checking Discord constantly feeling worried. I'm a very emotional person and I can care about people more than myself, which is inherently bad anyway. Now I often deal with many headaches, a lot of anxiety and panic attacks. I have considered to stop using Discord for a while but I would miss my friends and I'm only gonna hurt myself more by doing that. If this all seems silly to you... just leave...

## Installation

### Windows

- Discord: https://discordapp.com/download
- Python 3: https://www.python.org/downloads/

Then follow these steps:

- Save [forceful-unworry-discord.css](https://raw.githubusercontent.com/makitsune/forceful-unworry-discord/master/forceful-unworry-discord.css) somewhere permanent such as your Documents folder.
- Make sure Discord is running.
- Right mouse click inside the folder => `Open PowerShell window here`
```sh
python -m pip install -U https://github.com/leovoel/BeautifulDiscord/archive/master.zip
beautifuldiscord --css forceful-unworry-discord.css
```
If you want to revert, do:
```
beautifuldiscord --revert
```

### Linux

Make sure you have `python3` and `discord`. 

```sh
mkdir ~/.maki
curl -o ~/.maki/forceful-unworry-discord.css https://raw.githubusercontent.com/makitsune/forceful-unworry-discord/master/forceful-unworry-discord.css
python3 -m pip install -U https://github.com/leovoel/BeautifulDiscord/archive/master.zip
beautifuldiscord --css ~/.maki/forceful-unworry-discord.css
```

If you want to revert, do:
```
beautifuldiscord --revert
```
