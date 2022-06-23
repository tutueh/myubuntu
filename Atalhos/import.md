# Importar Configs

**Importar Keyboard Shortcuts**

```
cat dump_1 | dconf load /org/gnome/shell/keybindings/
cat dump_2 | dconf load /org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/custom0/
cat dump_3 | dconf load /org/gnome/settings-daemon/plugins/media-keys/
cat dump_4 | dconf load /org/gnome/desktop/wm/keybindings/
```

**Importar todas as Configs**

```
dconf load / < user.conf
```
