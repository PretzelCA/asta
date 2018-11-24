# Project ASTA

[![CircleCI](https://circleci.com/gh/PretzelCA/asta.svg?style=svg&circle-token=da4bbe2d56d4cb3ca352f99ee9fc06cc80b1b916)](https://circleci.com/gh/PretzelCA/asta)
10/10 best discord bot
[![Waffle.io - Columns and their card count](https://badge.waffle.io/PretzelCA/asta.svg?columns=all)](https://waffle.io/PretzelCA/asta)

## Getting Started

To add this bot to your Discord server, use [this](https://discordapp.com/oauth2/authorize?client_id=513198240922075137&scope=bot&permissions=8) link.

## Developing Project ASTA

In order to get started with Project ASTA you will need a couple of programs and files.

1. [GitHub Desktop](https://desktop.github.com/), in order to clone the repo and commit your changes you will need GitHub Desktop, it essentially is just a git client.

2. [Python 3.6.6](https://www.python.org/downloads/release/python-366/), Python 3.7 is not supported by discord.py and PyNaCl so using Python 3.6.6 is required. Make sure when installing you select the option "Add Python 3.6 to PATH"

3. flake8, flake8 is Project ASTA's linter and as such requires it to be installed and used. Install flake8 using `python -m pip install -U flake8` or `python3 -m pip install -U flake8` and then set your enviroment of choice to use flake8.

4. discord.py, to install discord.py, use `python -m pip install -U discord.py[voice]` or `python3 -m pip install -U discord.py[voice]
   ` in a terminal (On Windows use Powershell or Command Prompt).

5. Clone the repo, using GitHub Desktop, clone the repo.

6. Edit config.json, in the same folder as the repo rename config.json.example and edit it.

At this point you should be able to start the bot up and test it out.

A mirror of the code is located at [GitLab](https://gitlab.com/pretzelca/asta/tree/master)
