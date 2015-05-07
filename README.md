# ddmenu
dynamic dmenu heirarchy builder

This script builds a custom menu for performing common tasks. e.g. changing the volume, switching wireless networks via netctl, umounting disks, ...

### Example dwm configuration to call dmenu_custom on Mod+o
```
static const char *mydmenucmd[] = { "dmenu_custom", "-m", dmenumon, "-fn", dmenufont, "-nb",
    normbgcolor, "-nf", selbordercolor, "-sb", selbgcolor, "-sf", selfgcolor, NULL };
	{ MODKEY,                       XK_o,      spawn,          {.v = mydmenucmd } },
```
