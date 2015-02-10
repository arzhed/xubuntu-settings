# xubuntu-settings
my own settings and scripts for Linux fresh install (based on Xubuntu 14.04)

----
brightness
----

No script needed in the end as xbacklight offers all commands

sudo apt-get install xbacklight

xbacklight -set 50

xbacklight +10

----
keyboard brightness
---

Usage: sudo ./key-brightness.sh <digit>

      0 - keyboard backlight off

      1 - keyboard backlight on (level 1)

      2 - keyboard backlight on (level 2)

      3 - keyboard backlight on (level 3)

Credits : ktoso https://github.com/ktoso/g73-keyboard-backlight-sh
