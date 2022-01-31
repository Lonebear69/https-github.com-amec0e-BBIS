# BBIS
BugBounty Install Script

## Description:

A script I wrote to help me automate the installation of tools I use for hunting on a fresh Ubuntu/Raspberry Pi 4 install.


## Usage:

```
. ./BBIS
```

You do not need to use `sudo` unless you absolutely need to for some reason.

### Note For Oh-My-Zsh Users:

Oh-my-zsh by default ships with the plug-in (git) enabled. All this does is add a bunch of alias's for git which one of which is gau `git add --update` 

### Solution:

Either remove the git from plugins= in your .zshrc or rename the alias for gau before running the script to avoid conflicts. 

## Tools:

 - Anew
 - Amass
 - Aquatone
 - Arjun
 - Crawpy
 - Feroxbuster
 - Ffuf
 - Gau
 - Gitjacker (Not available in the Pi Version)
 - GitTools
 - Httprobe
 - SecLists + Assetnote Top 1m Parameters

## Requirements: (All included)

 - python3-pip
 - git
 - goland
 - chromium-browser
