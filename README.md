# Destiny 2 Solo Lobby Script
A script that allows you to disable matchmaking in Destiny 2, all this script does is adds firewall rules when first ran and if rules are already in place (second run) it will disable them and re enable match making. There are now two versions of this, one is a powershell script and one is an exe with two buttons, both you can see how to use below.

## Why use this? 

So you can do bounties etc alone and not with pesky people :) 

## Running The Script

Before trying to run the script you must allow Windows Powershell to run .ps1 files; Open PowerShell as Administrator and run the following commands to allow unsigned scripts to be executed:

```
set-executionpolicy remotesigned
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

If prompted, enter `A` for `Yes to All` into the Powershell command line prompt.

![howto](http://mrpl.me/pc1046b_rfx3.gif)

Once you have done that, right click the script > open with > windows powershell, don't worry if its blank, sometimes text wont load, if this is the case press any key. (if it closes this is also ok)
