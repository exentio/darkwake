# Darkwake Color Scheme

Color scheme born when I decided that I didn't like blue (((keremorph))) that much.  
The colors are picked from the cover art of Awake Deluxe by Tycho.  
![alt text](https://raw.githubusercontent.com/exentio/darkwake/master/awake_deluxe.jpg "Awake Deluxe cover art")

![alt text](https://raw.githubusercontent.com/exentio/darkwake/master/preview.png "Preview")

### Colors

    Background:     #30373D
    Text/Fore:      #BEC2A9
    Black:          #3E495F
    Red:            #B67466
    Green:          #9C6762
    Yellow:         #AF717E
    Blue:           #8e6176
    Magenta:        #8f6d88
    Cyan:           #6f6b82
    White:          #c8c9c1

### How to add the scheme in .Xresources

I decided to use a modular approach, inspired by [dkeg](https://github.com/dkeg) (this means darkwake is compatible with his schemes).
To add the scheme to .Xresources, simply paste this into the file, after other settings, and remove the previous colors if present:

    #include <darkwake/darkwake>        ! - Change this if the repo isn't inside ~/darkwake

    ! Colors
    *background:   bg
    *foreground:   fg
    *cursorColor:  cyn

    *color0:      blk
    *color8:      bblk
    *color1:      red
    *color9:      bred
    *color2:      grn
    *color10:     bgrn
    *color3:      ylw
    *color11:     bylw
    *color4:      blu
    *color12:     bblu
    *color5:      mag
    *color13:     bmag
    *color6:      cyn
    *color14:     bcyn
    *color7:      wht
    *color15:     bwht

### How to install themes

That's pretty simple: just copy the folder inside `~/.themes` and apply it with `llxappearance` for GTK and `obconf` for Openbox

### How to install the Chromium/Google Chrome theme

Simply drop it inside the window