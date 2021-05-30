---
title: Tech Setup
author: Richard Xu
categories: [Random]
tags: [random]
math: true
---

This is a super chill post! My old laptop was getting quite old and I recently got a new one. During installation I had some time to reflect on the tech choices / apps I use. My setup is quite minimal, and I thought I would share the tools in case anyone find this useful.

# Overall Setup
I use a Macbook running Windows on Bootcamp. As a Windows user since 2003, I love it. However, I have always been impressed by the build quality of a Macbook. Furthermore, it is occasionally helpful to have both OS. For example, I could debug compers' setup issues more easily during the Crimson tech comp. Also, when some installation fails horribly on one OS, I can also switch to the other one.

To find good apps, I usually start by reading the `awesome` page for the product on Github. For example, here are the links to [Awesome Mac](https://github.com/jaywcjlove/awesome-mac), [Awesome Windows](https://github.com/Awesome-Windows/Awesome) and [Awesome VSCode](https://github.com/viatsko/awesome-vscode). These pages contain tools that developers have found useful, and I found that they generally work better than simple Googling.

# MacOS
I don't have anything specific in MacOS, since I use it less often than Windows. The main items are
1. `homebrew` for programming languages.
2. VSCode as a general code editor.
3. Notion for notes.
4. Chrome for general browsing.

# Windows
Here are the apps I use.
1. Adobe Creative Cloud for occasional photo/video edits. Harvard has a deal that makes it free.
    1. Audacity here too.
2. Microsoft Office for occasional word / excel documents. Similarly, this is free thanks to some deal.
3. Zoom for video calls, Discord for occasional chats.
4. A VPN and Netflix.
5. VSCode/Notion/Chrome like before.
6. Google Drive with sync on, except for some large files.
7. Accessories: 7zip, Autohotkey, f.lux.

## VSCode
Other than the intellisense packages for each language I code in, I also use the Horizon theme, Material Icon Theme, Gitlens and `vscode-pdf`.

# Ubuntu
I am using WSL 2 on Windows, which has most of the features of Linux. Programming on Linux is much easier to setup, hence the choice.
1. `python-pip3`, `openjdk`, `opam` for Python/Java/OCaml. C++ comes preinstalled, so I didn't need to worry about that.
2. Some [OCaml Packages](https://dev.realworldocaml.org/install.html).
3. `nodejs` and `npm` for Crimson work, as well as a few python packages.

Since VSCode is installed, I can use `code` to code in a familiar environment.

In python, of course, I need to get a few packages too:
1. `numpy` / `pandas` for general data stuff.
2. `jupyterlab` for general research projects.
3. `torch` and `tensorflow` for the occasional ML projects.