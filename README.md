# kiss-i3wm
A repo for Kiss Linux to install i3wm.

Kiss Linux: https://k1ss.org/

After adding xorg and community repos and installing X (`kiss b xorg-server xinit xf86-input-libinput`),
add this repo and then add its local path to KISS_PATH, then:

```
# kiss b i3
-> Resolving dependencies
-> Building: autoconf automake libev startup-notification xcb-util xcb-util-image xcb-util-renderutil xcb-util-cursor xkbcommon yajl pcre gperf fontconfig cairo fribidi libXft pango i3
-> Continue? Press Enter to continue or Ctrl+C to abort here
```



