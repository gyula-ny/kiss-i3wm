# kiss-i3wm
A repo for Kiss Linux to install i3wm [wip, nothing works yet]

Kiss Linux: https://k1ss.org/


i3 Dependencies:
```
┌──────────────┬────────┬────────┬─────────────────────────────────────────────────────────────┐
│ dependency   │ min.   │ lkgv   │ URL                                                         │
├──────────────┼────────┼────────┼─────────────────────────────────────────────────────────────┤
│ pkg-config   │ 0.25   │ 0.29   │ https://pkgconfig.freedesktop.org/                          │
│ libxcb       │ 1.1.93 │ 1.12   │ https://xcb.freedesktop.org/dist/                           │
│ xcb-util     │ 0.3.3  │ 0.4.1  │ https://xcb.freedesktop.org/dist/                           │
│ xkbcommon    │ 0.4.0  │ 0.6.1  │ https://xkbcommon.org/                                      │
│ xkbcommon-x11│ 0.4.0  │ 0.6.1  │ https://xkbcommon.org/                                      │
│ util-cursor³⁴│ 0.0.99 │ 0.1.3  │ https://xcb.freedesktop.org/dist/                           │
│ util-wm⁴     │ 0.3.8  │ 0.3.8  │ https://xcb.freedesktop.org/dist/                           │
│ util-keysyms⁴│ 0.3.8  │ 0.4.0  │ https://xcb.freedesktop.org/dist/                           │
│ util-xrm⁴    │ 1.0.0  │ 1.0.0  │ https://github.com/Airblader/xcb-util-xrm/                  │
│ libev        │ 4.0    │ 4.19   │ http://libev.schmorp.de/                                    │
│ yajl         │ 2.0.1  │ 2.1.0  │ https://lloyd.github.com/yajl/                              │
│ asciidoc     │ 8.3.0  │ 8.6.9  │ http://www.methods.co.nz/asciidoc/                          │
│ xmlto        │ 0.0.23 │ 0.0.23 │ http://www.methods.co.nz/asciidoc/                          │
│ Pod::Simple² │ 3.22   │ 3.22   │ http://search.cpan.org/dist/Pod-Simple/                     │
│ docbook-xml  │ 4.5    │ 4.5    │ http://www.methods.co.nz/asciidoc/                          │
│ PCRE         │ 8.12   │ 8.38   │ https://www.pcre.org/                                       │
│ libsn¹       │ 0.10   │ 0.12   │ https://freedesktop.org/wiki/Software/startup-notification/ │
│ pango        │ 1.30.0 │ 1.40.1 │ http://www.pango.org/                                       │
│ cairo        │ 1.14.4 │ 1.14.6 │ https://cairographics.org/                                  │
└──────────────┴────────┴────────┴─────────────────────────────────────────────────────────────┘
 ¹ libsn = libstartup-notification
 ² Pod::Simple is a Perl module required for converting the testsuite
   documentation to HTML. See https://michael.stapelberg.de/cpan/#Pod::Simple
 ³ xcb-util-cursor, to be precise.
 ⁴ Depending on your distribution, this might be considered part of xcb-util.
```

```
# kiss b i3
-> Resolving dependencies
-> Building: autoconf automake libev startup-notification xcb-util xcb-util-image xcb-util-renderutil xcb-util-cursor xkbcommon yajl pcre gperf fontconfig cairo fribidi libXft pango i3
-> Continue? Press Enter to continue or Ctrl+C to abort here
```



