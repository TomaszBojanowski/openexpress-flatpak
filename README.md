# openExpress Flatpak repository

This repository hosts the Flatpak repository for
[openExpress](https://github.com/TomaszBojanowski/openExpress), an unofficial
Garmin Express client for Linux. It is published via GitHub Pages at
<https://flatpak.bojanowski.me/>.

For source code, issues and documentation, see the
[main repository](https://github.com/TomaszBojanowski/openExpress).

## Installation

```sh
flatpak remote-add --user --if-not-exists openexpress https://flatpak.bojanowski.me/openexpress.flatpakrepo
flatpak install openexpress io.github.tomaszbojanowski.OpenExpress
```

Updates arrive through a regular `flatpak update`.
