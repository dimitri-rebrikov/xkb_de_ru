# xkb_de_ru
russian phonetic layout on the german QWERTZ keyboard (Linux)

sudo cp de /usr/share/X11/xkb/symbols/de
sudo rm /var/lib/xkb/*.xkm
sudo setxkbmap -layout "de,de" -variant ",ru" -option "grp:ctrl_shift_toggle"
sudo cp keyboard /etc/default/keyboard

