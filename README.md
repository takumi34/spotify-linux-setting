# spotify-linux-setting
spotify's app in Linux is not scaling in HDPI display.

1. Edit the setting file. 
```bash
sudo vim /var/lib/snapd/desktop/applications/spotify_spotify.desktop
```
2. Add this. In my laptop, 2.5 is better.
```bash
--force-device-scale-factor=2.5
```
