#Minimal Nord i3 
## Preview:

![Preview](preview.png)
![Preview](preview2.png)

## Things to remember:
* The status bar is *tint2* and it uses the given *tint2rc_split*.
* The scripts *multistat*, *toDo*, *clearToDo* and *modToDo* must be stored in /bin/
* The scripts *music.sh, info.sh, musicstat.sh, time.sh* must be stored in the HOME directory.
* To play music, your songs must be stored in *~/Music/All*
* The rofi theme *rofi.rasi* must be saved in /usr/share/rofi/themes/ and can be activated using rofi-theme-selector.
* *.wallpaper.jpg* and *.wallpaper2.jpg* should be in the HOME directory.

## The bar:
![Tint2 Bar](tint2_bar.png)
* The tint2 bar is running the *info.sh, musicstat.sh, time.sh* scripts for status.
* Scroll for adjusting volume.
* Left and right click for switching workspaces.
* Left Click on the music module for playing music and right click for stopping music.

## Programs required:
* Rofi
* tint2
* sox (for music)
* xfce4-terminal (optional, but can be used with the terminalrc for the colorscheme)
