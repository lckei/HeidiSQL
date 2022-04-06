# HeidiSQL
Heidisql 11.3  appimage

require wine.
You can download `wine-stable_7.0.0.0-x86_64.AppImage` from https://github.com/mmtrt/WINE_AppImage/releases .
Then run: `chmod +x $(pwd)/wine-stable_7.0.0.0-x86_64.AppImage; sudo ln -s $(pwd)/wine-stable_7.0.0.0-x86_64.AppImage /usr/bin/wine`

```
$ chmod +x $(pwd)/HeidiSQL-x86_64.AppImage 
$ $(pwd)/HeidiSQL-x86_64.AppImage 
```

Success running on Debian buster bullseye; Deepin 20.x ; Ubuntu 20.x.
