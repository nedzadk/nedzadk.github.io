---
layout: post
title: Dell XPS 9560 - The perfect Linux distro
tags:
  - linux
  - dell
---

My adventure trying to get Linux running without issues on Dell XP 9560 (4k version with Killer Wifi)
is finally over.

I've tried different distros and all of them had different type of issues. Some of them had problem switching between
integrated and dedicated GPU, other (most of them) had problem where Wifi would not work or would disconnect randomly and
reboot was necessary to get it working again, increased power consumption was not rare also.

I should also mention that installation process for all distros is something that requires you to add `nomodeset` or some other
flags before booting into installation.

All above issues are resolved once i gave _Pop!\_OS_ chance. Everything worked out of the box. Installation process did not require
special configuration just to run it, and if you download Nvidia ISO of _Pop!\_OS_ your integrated and dedicated GPUs work out of the box (it does require reboot on switching but at least it works each time as expected and since i do not use Nvidia GPU most of the time this is not issue for me).

![neofetch](/images/pop_os_ss.jpg)

Even though _Pop!\_OS_ is based on Ubuntu, guys from System76 added something to make it more compatible with modern hardware than Ubuntu is.

With this my search for Linux distro that will not cause me to pull my hair couple times a day is finally over. I've been running it for more than a month now
with not a single issue during that time. Everything works like charm.

If you want to give it a try, get _Pop!\_OS_ here: [https://system76.com/pop](https://system76.com/pop)

P.S.
I am in no way related to System76 and have not been compensated for this shout out!
