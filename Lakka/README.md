# Scripts for Lakka

This integration supports all [Lakka](http://www.lakka.tv/) (Libretro-RetroArch) native functions, including software updates, etc...


Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installLakka https://bit.ly/InstLakka; chmod u+x installLakka; ./installLakka
```
and follow onscreen instructions to install a patched Lakka image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot) (screen & keyboard strongly advised).

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)


### supported features:
- ~~Software update through Lakka UI~~ (note: updated image will automatically be patched with latest patch version available) will work as soon as a [longstanding Lakka/RetroArch bug](https://github.com/libretro/Lakka-LibreELEC/issues/281) is fixed...
- patch log available in system journal



### changelog:
1.2:  (December 31st 2018)
- bootdev= parameter in cmdline.txt not mandatory anymore

1.1:  (October 28th 2018)
- change redirector

1.0:  (October 31st 2017)
- initial version
