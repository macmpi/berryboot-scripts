# Scripts for LibreELEC

This integration supports all LibreELEC native functions, including software updates, reset (soft/hard), backup restore, etc...


Short tip: from any Debian-based distribution (Raspbian under berryboot advised), run the following 1-line command:
```
curl -Ls --output installLibreELEC http://bit.do/InstLE; chmod u+x installLibreELEC; ./installLibreELEC
```
and follow onscreen instructions to install a patched LibreELEC image on your berryboot media.

That patched image will then natively support all features, as would the standalone distribution.






## supported features:
- Software update through LibreELEC UI: manual & auto modes (note: updated image will automatically be patched with latest patch version available)
- Soft / Hard reset through LibreELEC UI
- Backup restore through LibreELEC UI
- patch log available in system journal



## changelog:
1.0:  (October 22nd 2017)
- initial version
