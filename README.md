# BBIS
BugBounty Install Script

## Description:

A script I wrote to help me automate the installation of tools I use for hunting on a fresh Ubuntu install.


## Usage:

```
. ./BBIS
```

**NOTE For Oh-My-ZSH Users**

Oh-my-zsh by default ships with the plug-in (git) enabled. All this does is add a bunch of alias's for git which one of which is(gau) `git add --update` Either remove the git from plugins= in your .zshrc or rename the alias for gau before running the script to avoid conflicts. 

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
