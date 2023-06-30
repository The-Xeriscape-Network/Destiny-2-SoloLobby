# Destiny 2 matchmaking disable
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

Note: Both of the commands above still need to be ran.

When disabling: http://mrpl.me/P31047b_rfs8.png

When enabling: http://mrpl.me/l21048b_rff8.png

# Downloads

Download: https://github.com/MrPleasant-exe/Destiny-2-Solo-lobby/releases

Special thanks to various Reddit users for the specific ports etc


<img src="https://img.shields.io/github/downloads/MrPleasant-exe/Destiny-2-Solo-lobby/total?style=social" alt="Downloads"/><img src="https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2FMrPleasant-exe%2FDestiny-2-Solo-lobby
" alt="Twitter"/>

<img src="https://img.shields.io/github/last-commit/MrPleasant-exe/Destiny-2-Solo-lobby/master" alt="Commit"/>


