# archraft-mirrorlist
Mirrors from archcraft so you can use the rices in any other arch-based distro.

Installation:

cd /etc/pacman.d

sudo wget https://raw.githubusercontent.com/jensgrunzer1/archraft-mirrorlist/main/archcraft-mirrorlist

Append the following to /etc/pacman.conf:

[archcraft]

SigLevel = Optional TrustAll

Include = /etc/pacman.d/archcraft-mirrorlist
