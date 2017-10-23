# Scripts for Volumio 2

This integration supports all Volumio2 native functions, including software updates, User-data / Factory reset, etc...


You may refer [here](https://volumio.org/forum/multiboot-volumio2-with-kodi-under-berryboot-t6818.html#p33742) for detailed information and install procedure.

Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installVolumio2 http://bit.do/InstV2; chmod u+x installVolumio2; ./installVolumio2
```
and follow onscreen instructions to install a patched Volumio2 image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.



## supported features:
- Software update through Volumio2 UI (note: updated image will automatically be patched with latest patch version available)
- User Data / Factory reset through Volumio2 UI
- Swap on lower memory devices (note: may be disabled by adding /nowsap file from Volumio2 shell)
- patch log available in system journal



## changelog:
1.0:  (October 19th 2017)
- initial version
