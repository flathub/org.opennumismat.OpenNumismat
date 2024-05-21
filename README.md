# OpenNumismat

OpenNumismat is a software for management custom coin collection catalog.

This repo hosts the flatpak wrapper for [OpenNumismat](https://opennumismat.github.io/), available at [Flathub](https://flathub.org/apps/org.opennumismat.OpenNumismat).

```sh
flatpak install flathub org.opennumismat.OpenNumismat
flatpak run org.opennumismat.OpenNumismat
```

### Wayland

This package uses the flags to run on Wayland. To opt-out it run:

```sh
flatpak override --user --nosocket=wayland org.opennumismat.OpenNumismat
```
