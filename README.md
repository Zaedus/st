# My st config

Like my dwm config, this is mostly from [DistroTube's config](https://gitlab.com/dwt1/st-distrotube). However, what is different is the colors, which I got from [JavaCafe01's st config](https://github.com/JavaCafe01/st)

## Patches

+ st-alpha -- adds transparency to the background (must have a compositor for this to work)
+ st-font2 -- adds the option to list multiple fonts; great for having a fallback font
+ st-ligatures -- ligature support; requires harfbuzz
+ st-scrollback -- adds scrollback with SHIFT+PageUp/PageDown
+ st-scrollback-mouse -- adds the ability to scroll with SHIFT+MouseWheel
+ st-scrollback-mouse-altscreen -- now you can scroll with just the MouseWhell (no SHIFT required)
+ st-vertcenter -- better vertical alignment of lineszz
+ st-workingdir -- adds option to open st at specific directory (ex: st -d /usr/bin)

## Installation

```
git clone https://github.com/Zaedus/st.git
cd st
sudo make clean install
```

> NOTE: This will overwrite any previous st config. Make sure to back it up!