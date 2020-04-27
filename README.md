# robo3t-flatpak
Unofficial Flatpak package of Robo3t  


First of all, you need org.kde.Sdk//5.14

```
flatpak install flathub org.kde.Sdk//5.14 --user -y
```

You can then build and install Robo3t using
```
flatpak-builder --install repo org.robomongo.Robo3T.json --user -y
```


### Credits
The metainfo and desktop file are based on work by https://github.com/nexcode