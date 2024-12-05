<h1 align="center"> matrix lockscreen theme for sway </h1>

<h3 align="center"> This script is intended for sway compositor. </h3>
<h3 align="center"> MIT license </h3>

**Make sure you have already installed:**

1. [swaylock-effects](https://github.com/mortie/swaylock-effects) by mortie 
2. [kitty](https://github.com/kovidgoyal/kitty) by kovidgoyal (You may use another terminal, but would need to edit files by hand)
3. [cmatrix](https://github.com/abishekvashok/cmatrix) by abishekvashok OR [unimatrix](https://github.com/will8211/unimatrix) by will8211 (If you have both, the script will prioritize unimatrix)

Have these packages installed. Run the scripts, and choose the colors and transparency. 
Then, add on hyprland config file the bindsym command with the script:
```
    # Sway lock
    bindsym $mod+M exec "/home/wren/.config/swaylock/lockscript.sh"

```
After that, you can use the script to quickly change colors.

This script is intended for sway compositor, But you can use the script to adapt to your Wayland environment.
