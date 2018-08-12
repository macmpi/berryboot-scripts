# Scripts for LibreELEC

This integration supports all [LibreELEC](https://libreelec.tv/) native functions, including software updates, reset (soft/hard), backup restore, etc...


Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installLibreELEC http://bit.do/InstLE; chmod u+x installLibreELEC; ./installLibreELEC
```
and follow onscreen instructions to install a patched LibreELEC image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot) (screen & keyboard strongly advised).
In `cmdline.txt` file on boot partition, you MUST set `bootdev=` parameter to point to the used berryboot boot partition such as `mmcblk0p1` or `sda1` (berryboot installer does not always do it, which may cause issues). Reboot after the change.

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)


### supported features:
- Software update through LibreELEC UI: manual & auto modes (note: updated image will automatically be patched with latest patch version available)
- Soft / Hard reset through LibreELEC UI
- Backup restore through LibreELEC UI
- patch log available in system journal



### changelog:
1.2:  (August 12th 2018)
- support for Milhouse [custom beta builds install](https://forum.kodi.tv/showthread.php?tid=298461)

1.1:  (October 29th 2017)
- support all update files

1.0:  (October 22nd 2017)
- initial version
