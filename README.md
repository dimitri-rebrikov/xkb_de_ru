# xkb_de_ru
russian phonetic layout on the german QWERTZ keyboard

sudo cp de /usr/share/X11/xkb/symbols/de
sudo rm /var/lib/xkb/*.xkm
sudo setxkbmap -layout "de,de" -variant ",ru" -option "grp:alt_shift_toggle"

