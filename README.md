# config-hyprland

1. Télécharger tous les packages avec pacman (cf fichier pacman-packages)
2. Séparer les fichiers de ~/.config/hypr/hyprland.conf en plusieurs fichiers dans le dossier hypr (par exemple binds en copie collant la fin du hyprland.conf). Attention il faut rajouter `source = ~/.config/hypr/binds.conf` APRES avoir déclaré les variables (par ex $terminal = kitty).
3. Déplacer le dossier de config de waybar. `mv /etc/xdg/waybar ~/.config/waybar`
4. Copier coller le dossier hypr dans ~/.config/hypr
