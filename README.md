# st - simple terminal

Patched version with own configuration of st from https://st.suckless.org

Following patches are installed:

* **[scrollback](https://st.suckless.org/patches/scrollback)** - scroll function `Shift`+{`PageUp`,`PageDown`} or mousewheel
* **[alpha](https://st.suckless.org/patches/alpha)** - change opacity of the background (composite manager needed)

Terminal Colors are also slightly different, here is the palette:

![16 Terminal Colors](colors.png)

(dark colors are boosted to make them more visible on the black background)

```c
    	// 8 normal colors 
	"black",
	"red3",
	"green3",
	"yellow3",
	"SkyBlue3",
	"DarkOrchid3",
	"cyan3",
	"#D0CFCC",

	// 8 bright colors
	"#5E5C64",
	"red1",
	"green1",
	"yellow1",
	"SkyBlue1",
	"DarkOrchid1",
	"cyan1",
	"white",
```
