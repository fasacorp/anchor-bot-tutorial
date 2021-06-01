# Anchor bot tutorial from dummies

## Risks disclaimer

This tutorial provided instructions on how to get anchor-bot from Romain Lanz to run on a regular window machine.

> ⚠️ Running anchor bot on windows is inherently more risky than running on a linux box as linux is much more stable. I recommend running the anchor bot on a headless linux installation on raspeberry pi or nuc or similar.

YOU ARE RUNNING THE BOT AT YOUR OWN RISK AN I DECLINE EXPLICITELY ANY LOSS THAT MAY ARISE DUE TO THIS TUTORIAL.

## Software requirements
On windows you will need:
1. powershell: It will make using command line on windows much less painfull.
2. node.js: The executable environment to run the bot.
3. Station wallet: to create a wallet for your bot.

### Powershell installation
The best way to install PowerShell is via the [microsoft store](https://www.microsoft.com/en-gb/p/powershell/9mz1snwt0n5d?rtc=1&activetab=pivot:overviewtab) and is the recommended way to go.

I also recommend you pin powershell to your task bar.

### Node.js installation
Node.js installation is available [here](https://nodejs.org/en/download/) for download and install. Just run the installation.

### Station wallet
Do I really need to explain that one? Nahh we are good.

### Making sure it's all working.
Start powershell and in the prompt enter the following command.
```
PS > npm -h
PS C:\Users\romain> npm -h

Usage: npm <command>

where <command> is one of:
    access, adduser, audit, bin, bugs, c, cache, ci, cit,
    clean-install, clean-install-test, completion, config,
    create, ddp, dedupe, deprecate, dist-tag, docs, doctor,
    edit, explore, fund, get, help, help-search, hook, i, init,
    install, install-ci-test, install-test, it, link, list, ln,
    login, logout, ls, org, outdated, owner, pack, ping, prefix,
    profile, prune, publish, rb, rebuild, repo, restart, root,
    run, run-script, s, se, search, set, shrinkwrap, star,
    stars, start, stop, t, team, test, token, tst, un,
    uninstall, unpublish, unstar, up, update, v, version, view,
    whoami

npm <command> -h  quick help on <command>
npm -l            display full usage info
npm help <term>   search for help on <term>
npm help npm      involved overview

Specify configs in the ini-formatted file:
    C:\Users\romain\.npmrc
or on the command line via: npm <command> --key value
Config info can be viewed via: npm help config

npm@6.14.11 C:\Program Files\nodejs\node_modules\npm
PS C:\Users\romain>
```

## Installing the bot

The easiestway to get started is to download a copy of the [code repository](https://github.com/RomainLanz/anchor-borrow-bot). To do that you can go in Code => Download zip.

The rest of this tutorial assumes that you have downloaded the ZIP file and unzipped it into 'Document > Anchor Bot > anchor-borrow-bot-main' folder.

Now we will install all the dependencies to run the bot:

```
PS > cd ~/Documents
PS > cd '.\Anchor bot\anchor-borrow-bot-main\'
PS > npm install
```

Now we will test that t


