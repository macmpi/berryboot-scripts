# Scripts for Lakka

This integration supports all [Lakka](http://www.lakka.tv/) (Libretro-RetroArch) native functions, including software updates, etc...


Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installLakka http://bit.do/InstLk; chmod u+x installLakka; ./installLakka
```
and follow onscreen instructions to install a patched Lakka image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot).
In `cmdline.txt` file on boot partition, you MUST set `bootdev=` parameter to point to the used berryboot boot partition (berryboot installer does not always do it, which may cause issues)

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)


### supported features:
- Software update through Lakka UI (note: updated image will automatically be patched with latest patch version available)
- patch log available in system journal



### changelog:
1.0:  (October 31st 2017)
- initial version
