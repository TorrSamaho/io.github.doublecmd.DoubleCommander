# Install prerequisites
```
flatpak install --user flathub org.kde.Platform//5.15-23.08 org.kde.Sdk//5.15-23.08 flathub org.freedesktop.Sdk.Extension.freepascal//23.08 flathub org.flatpak.Builder
```
# Build and install (using the flatpak version of flatpak-builder)
```
flatpak run org.flatpak.Builder --disable-rofiles-fuse --force-clean build-dir io.github.doublecmd.DoubleCommander.yml
flatpak run org.flatpak.Builder --user --install --force-clean build-dir io.github.doublecmd.DoubleCommander.yml
```
