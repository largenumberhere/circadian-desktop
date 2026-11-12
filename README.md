# Circadian Service
A quick and dirty script to update the desktop settings to help with human circadian rythm / daylight cyles.


## Implementation hints
 cp desktopcircadian.service ~/.config/systemd/user/

 systemctl --user restart desktopcircadian.service 
 systemctl --user status desktopcircadian.service 
(points to: `./backgroundupdate.sh`)

 gsettings get-keys org.gnome.desktop.background
 gsettings list-keys org.gnome.desktop.background
 gsettings get org.gnome.desktop.background picture-uri
 gsettings get org.gnome.desktop.background picture-uri-dark
 gsettings list-keys 
 gsettings list-schemas

gsettings get org.gnome.desktop.interface gtk-theme
'Yaru-red-dark'
gsettings get org.gnome.desktop.interface gtk-theme
'Yaru-dark'
gsettings get org.gnome.desktop.interface gtk-theme
'Yaru-blue'
gsettings get org.gnome.desktop.interface gtk-theme
'Yaru-olive'
