lutris battle.net "Creating 64bit Wine prefix"

https://www.google.com/search?q=lutris+battle.net+%22Creating+64bit+Wine+prefix%22

# Discuss:
- https://forums.lutris.net/t/error-installing-battle-net-stucked-on-creating-64bit-wine-prefix/20703
- https://forum.endeavouros.com/t/creating-64bit-wine-prefix/60994
- https://www.reddit.com/r/linux_gaming/comments/kpjpn3/lutris_stuck_on_creating_wine_prefix/

# Solution:
```
sudo dpkg --add-architecture i386 && sudo apt update && sudo apt install -y wine64 wine32 libasound2-plugins:i386 libsdl2-2.0-0:i386 libdbus-1-3:i386 libsqlite3-0:i386
```
https://forum.endeavouros.com/t/creating-64bit-wine-prefix/60994/3

https://github.com/lutris/docs/blob/2b116519c5b67254733234f36ab33a60f14f1358/WineDependencies.md
