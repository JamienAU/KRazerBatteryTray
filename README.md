# KRazerBatteryTray
KDE tray application to show details for Razer peripheral battery status.

# Dependencies
- OpenRazer
- Python
  - PyQt6

# Usage
```
git clone https://github.com/JamienAU/KRazerBatteryTray.git
cd KRazerBatteryTray
sudo dnf install openrazer-meta
sudo dnf install PyQt6
Run KRazerBatteryTray, or in terminal './KRazerBatteryTray & disown'
```

# Autostart
The following template can be used to create an AutoStart entry, create a new file `~/.config/autostart/KRazerBatteryTray.desktop` and modify the Exec path.
```
[Desktop Entry]
Exec=<filepath>/KRazerBatteryTray/KRazerBatteryTray
Icon=battery-good
Name=KRazerBatteryTray
Path=
Terminal=False
Type=Application
```
