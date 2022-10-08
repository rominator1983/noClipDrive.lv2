No Clip Drive
===

This [lv2 plugin](https://en.wikipedia.org/wiki/LV2) adds amplification/drive/distortion to the signal but does not introduce clipping allowing for more dynamics than comparable approaches.

Install
===
Install the pre compiled artifacts from https://github.com/rominator1983/noClipDrive.lv2/releases
- Create a new folder in your lv2 directory (For example ~/.lv2/ or /usr/lib/lv2 or /usr/local/lib/lv2/ would all work in Ubuntu Studio)
- Copy noClipDrive.so, manifest.ttl and noClipDrive.ttl to this new folder.
- Restart/refresh your lv2 host

Build on your own
===
-  `./waf configure`
-  `./waf build`
-  `sudo ./waf install`
- Restart/refresh your lv2 host
