# Install prerequisites
```
flatpak install --user flathub org.kde.Platform//6.8 org.kde.Sdk//6.8 flathub org.freedesktop.Sdk.Extension.freepascal//24.08 flathub org.flatpak.Builder
```
# Build and install (using the flatpak version of flatpak-builder)
```
flatpak run org.flatpak.Builder --disable-rofiles-fuse --force-clean build-dir io.github.doublecmd.DoubleCommander.yml
flatpak run org.flatpak.Builder --user --install --force-clean build-dir io.github.doublecmd.DoubleCommander.yml
```
