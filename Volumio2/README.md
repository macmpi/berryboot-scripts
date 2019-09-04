# Scripts for Volumio 2

This integration supports all [Volumio2](https://volumio.org/) native functions, including software updates, User-data / Factory reset, etc...


You may refer [here](https://volumio.org/forum/multiboot-volumio2-with-kodi-under-berryboot-t6818.html#p33742) for detailed information and install procedure.

Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installVolumio2 https://bit.ly/InstVolumio2; chmod u+x installVolumio2; ./installVolumio2
```
and follow onscreen instructions to install a patched Volumio2 image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



#### Prerequisite(s):
- *the obvious:* install Berryboot on a media, and do initial setup as per [this](http://www.berryterminal.com/doku.php/berryboot) (screen & keyboard strongly advised).

- **either** (preferred) install Raspbian image (lite is fine) under berryboot and open shell there, **or** plug your configured berryboot media into any Debian-based Linux machine under shell (Ubuntu & derivatives, Mint, Pixel, Debian, etc...)



### supported features:
- Software update through Volumio2 UI (note: updated image will automatically be patched with latest patch version available)
- User Data / Factory reset through Volumio2 UI.
- Swap on lower memory devices (note: may be disabled by adding /noswap file from Volumio2 shell)
- patch log available in system journal.
- `installVolumio2` script is available in volumio user home directory for installing more images if needed.



### changelog:
1.5:  (September 4th 2019)
- supports berryboot 20190612 & later

1.3:  (December 31st 2018)
- bootdev= parameter in cmdline.txt not mandatory anymore

1.2:  (October 28th 2018)
- change redirector

1.1:  (October 28th 2017)
- improve `/boot` & `/berryboot` mounts scheduling and `dynamicswap.service` dependency
- clean-up MrEngman drivers .conf

1.0:  (October 19th 2017)
- initial version
