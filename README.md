![The Get-Pak logo.](logo.png)

**<h1 align="center">Get-Pak</h1>**
**<p align="center">**
**Now with less bugs! | [Download now!](#Downloading)**
**</p>**

## This thing, in a nutshell.

So, you've decided to buy a car (Linux Distro), it's rusty and it's not made for daily use (Ex. EyeVisionOS) but you still like it.

One day, you decide:

```
— Hey, I want to put a radio in this thing! (Program) —
- Famous last words before disaster.
```

So you go to the internet and search the radio and buy it. (Manually download the program, which is unusual, but stick with me!)

When it arrives though, you realize something: You don't got the tools to put it in! (DPKG, APT ect.)

You are sad now, but hope is not lost! You decide to buy a set of tools (Get-Pak) and you finally put the radio in, it's janky, but you did a great job!

## Downloading

Downloading is easy, you just have to make sure you have the dependencies:
This program requires `wget`, `curl` and other basic stuff that you surely have (Busybox has most of them).

Next, copy this command in your terminal (Run the last command as sudo if on normal Linux):
```shell
wget https://raw.githubusercontent.com/SCOS-Apps/get-pak/refs/heads/master/setup_get-pak && sh setup_get-pak
```
And done! You have yourself the program!
Remember to edit the `ARCH`, `repo_url` and `repo_dist` entries in the file that is located in `$PREFIX/bin/getpm` (Or `/bin/getpm` on Linux)

## Usage

Taken from the program itself:
```
Commands:
        --help | -h
                Show this dialog.
        --check-source | -chk
                Check if source is functional
        --create-pkg-list | -pkg
                Creates packages-full.list file to get packs.
        --download | -d
                Downloads packages and their dependencies.
        --download-batch | -b
                Downloads from dependencies lists.
```
