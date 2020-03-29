# Scripts for LibreELEC

This integration supports all [LibreELEC](https://libreelec.tv/) native functions, including software updates, reset (soft/hard), backup restore, etc...


Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installLibreELEC https://bit.ly/InstLibreELEC; chmod u+x installLibreELEC; ./installLibreELEC
```
and follow onscreen instructions to install a patched LibreELEC image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot) (screen & keyboard strongly advised).

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)


### supported features:
- Software update through LibreELEC UI: manual & auto modes (note: updated image will automatically be patched with latest patch version available)
- Soft / Hard reset through LibreELEC UI
- Backup restore through LibreELEC UI
- patch log available in system journal



### changelog:
1.6:  (March 29th 2020)
- fix UUID extraction

1.5:  (September 4th 2019)
- supports berryboot 20190612 & later

1.4:  (December 31st 2018)
- bootdev= parameter in cmdline.txt not mandatory anymore

1.3:  (October 28th 2018)
- change redirector

1.2:  (August 12th 2018)
- support for Milhouse [custom beta builds install](https://forum.kodi.tv/showthread.php?tid=298461)

1.1:  (October 29th 2017)
- support all update files

1.0:  (October 22nd 2017)
- initial version
