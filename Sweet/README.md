
![](Art/Sweet-theme.png)

## Installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/` or `~/.themes/` (create it if necessary).

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Sweet"
gsettings set org.gnome.desktop.wm.preferences theme "Sweet"
```
or Change via distribution specific tool.

## Modifications

- Nothing major i just saved my theme in both ~/.themes/ and /usr/share/themes/.
- I have a link between `.themes/Sweet/gtk-3.0/gtk-dark.css` and `/usr/share/themes/Sweet-Dark/gtk-3.0/gtk-dark.css` using
    - ln .themes/Sweet/gtk-3.0/gtk-dark.css /usr/share/themes/Sweet-Dark/gtk-3.0/gtk-dark.css
- This is all that is making the changes sass .themes/Sweet/gtk-3.0/gtk-dark.scss .themes/Sweet/gtk-3.0/gtk-dark.css  
