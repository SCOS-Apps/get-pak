![The Get-Pak logo.](logo.png)

**<h1 align="center">Get-Pak</h1>**
**<p align="center">**
**Now with less bugs! | [Download now!](#Downloading)**
**</p>**

# This thing, in a nutshell.

So, you've decided to buy a car (Linux Distro), it's rusty and it's not made for daily use (Ex. EyeVisionOS) but you still like it.

One day, you decide:

```
— Hey, I want to put a radio in this thing! (Program) —
- Famous last words before disaster.
```

So you go to the internet and search the radio and buy it. (Manually download the program, which is unusual, but stick with me!)

When it arrives though, you realize something: You don't got the tools to put it in! (DPKG, APT ect.)

You are sad now, but hope is not lost! You decide to buy a set of tools (Get-Pak) and you finally put the radio in, it's janky, but you did a great job!

# Downloading

Downloading is easy, you just have to make sure you have the dependencies:
This program requires `wget`, `curl` and other basic stuff that you surely have.

Next, copy this command in your terminal:
```
wget https://raw.githubusercontent.com/SCOS-Apps/get-pak/refs/heads/master/getpm; nano getpm; sudo cp getpm /usr/bin && sudo chmod 755 /usr/bin/getpm && sudo chown 0 /usr/bin/getpm
```
It will show the editing screen, if you don't have nano then edit this command to use other stuff.

From the editing screen, you'll need to make basic changes, such as your architecture, and which repo you wanna use, it defaults to the Debian one.

And done! You have yourself the program!
