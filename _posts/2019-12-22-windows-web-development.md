---
layout: post
title: Using Windows for Web development in 2020 (State of WSL2)
tags:
  - windows
  - dell
  - wsl2
  - vscode
  - windows insider
---
![WSL2/Ubuntu and Windows Terminal](../images/screen2.png)
For the last 7+ years, I've been using macOS and MacBooks exclusively for work and everything else. My development is mostly with Javascript (React, Node, Angular) but couple projects run on Ruby on Rails, Python and sometimes Java.

I am a big fan of Macbooks and Apple but I also think that hardware price is too much and for the same price you can get a much better laptop elsewhere (except touch bar, no other laptop touch bar can match one on MacBook still). I always wanted to make a switch but I knew that I would be greeted with tons of issues and missing software. 

I know you probably ask why not Linux? Well I did gave Linux a try a lot, and although most dev stuff works perfectly on Linux, modern hardware support, software support (no, GIMP is no alternative to Photoshop and it probably will never be) and UX experience is I think at least 10 years behind Windows or macOS. 

So I waited for Microsoft to wake up and start fighting for developers out there, and they kind of did.

## WSL

In 2016 Microsoft announced a WSL (Windows Linux Subsystem) worthy alternative to Unix Roots of MacOS. WSL was Linux "compatibility layer" that allowed Windows to run Linux applications.

It sounded so cool but in reality, it was bad, you could not run every Linux application it is painfully slow in I/O operations. When installing the npm packages process could take minutes when in reality should have been done in seconds. 

I would also love to mention that no good terminal emulator was available, the best one that I've used with WSL was ConEmu or starting X Server and using Linux Terminator. 

Over the years I gave WSL a couple of chances to impress me but it always failed to do so. So I stopped trying and went back to macOS. 

## New Hope (WSL2 or what WSL should have been)

But all was not lost, early in 2019 Microsoft introduced WSL2 with real Linux kernel this time and promised that it will solve all issues that WSL had. WSL2 runs as a lightweight virtual machine that is super fast that you sometimes might confuse it with real hardware (at least is what I heard).

So I waited a couple of versions and decided to give Windows another try as my main development machine* with Windows Insider version and beta WSL2 not expecting much but boy I was so wrong. 

I am currently writing this from the Windows machine that I use as my main fulltime dev station, and I can say that I am happy. In the past four weeks, not a single thing made me regret switch (which happened a couple of times a day when used WSL1). 
WSL2 is as fast as it can be, Windows integration with Linux is so seamless that you forget you are running a virtual Linux system. You `cd` to project directory and type `code .`, Visual Studio Code (Windows version not WSL) would popup with your project loaded and ready to debug with remote debugger setup between windows and WSL and I did not have to do anything except installing VS Code for Windows, rest of the setup (remote debugger and other stuff) were installed automatically on first Visual Studio Code start. 

![WSL2/Ubuntu and Windows Terminal](../images/screen.png)

Latest Docker Edge version has WSL2 support also and it works perfectly when enabled (in Docker settings after installation). So far I used to run Postgres and MySql databases for development inside WSL and it worked perfectly. 

I should also mention that together with WSL2 Microsoft introduced Windows Terminal a new and up to date terminal that can be used with Powershell, CMD, and WSL Linux installations. It supports all fancy features you might need except splitting view horizontally/vertically (I miss this, but a little bit of tmux solves this issue). 

## Conclusion 

So as I said after four weeks I am pretty happy with setup*, not a single issue appeared and all my projects work without issues. I was able to be productive without thinking much about how to make tools work for me, they just do. 

I am really happy to see where "new" Microsoft is going and excited for 2020 once WSL2 is release to the public. I am sure by then it will be a perfect tool for developers out there waiting for good enough alternatives for their MacBooks. 


``` * Dell XPS 7390/13/FHD/16/512/i7 10510U  ```