# gnome-issues
Solutions and reference to common issues in GNOME desktop


## Force Alt + Tab only in current workspace

By default GNOME switches windows between all workspaces when you press alt + tab,
run the below command as non-root to disable that behaviour.

```bash
gsettings set org.gnome.shell.app-switcher current-workspace-only true
```
reference: [askubuntu] (https://askubuntu.com/questions/464946/force-alt-tab-to-switch-only-on-current-workspace-in-gnome-shell)
