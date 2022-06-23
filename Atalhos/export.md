# Exportar configurações


**Exportar Keyboard Shortcuts**

```
dconf dump /org/gnome/shell/keybindings/ > dump_1
dconf dump /org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/custom0/ > dump_2
dconf dump /org/gnome/settings-daemon/plugins/media-keys/ > dump_3
dconf dump /org/gnome/desktop/wm/keybindings/ > dump_4
```

**Exportar todas as Configs**

```
dconf dump / > user.conf
```
