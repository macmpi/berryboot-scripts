# berryboot integration scripts
Repo for (hopefully) usefull [berryboot](http://www.berryterminal.com/doku.php/berryboot) integration scripts for few popular distributions

For each supported Distibution, a 1-line shell command is provided to run the installer which downloads a genuine image, patches-it, and then installs it for use inside berryboot.

Such patched image is then capable of supporting all Distribution features by itself, including auto-updates, resets, etc...

Therefore, the 1-line install command is only needed (once) for initial image creation: such installed image is then totally "autonomous", as would be a regular native Distribution install.




#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot) (screen & keyboard strongly advised).
In `cmdline.txt` file on boot partition, you MUST set `bootdev=` parameter to point to the used berryboot boot partition such as `mmcblk0p1` or `sda1` (berryboot installer does not always do it, which may cause issues)

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)
