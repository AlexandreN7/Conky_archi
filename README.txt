Pour lancer conky au démarrage de gnome,
placer le script suivant dans : /usr/share/gnome/autostart/conky.desktop

#conky.desktop
[Desktop Entry]
Type=Application
Name=Conky
Comment=Start conky script
Exec=conky -d
OnlyShowIn=GNOME;
X-GNOME-Autostart-Phase=Application
