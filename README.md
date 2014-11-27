overlay-crossdev
================

Fix some ebuild to allow cross compiling them

If you want to add this overlay copy tharvik-crossdev.xml to
/etc/layman/overlays/ then add tharvik-crossdev to layman.
```
cp tharvik-crossdev.xml /etc/layman/overlays/
layman -S
layman -a tharvik-crossdev
```
