# Changelog

All notable changes to Tela Soplos Icons are documented in this file.

## [1.0.0-4] - 2026-11-14

### Fixed

- The Other button of the login screen (Plasma Login Manager) fell back to a white outline of another theme, because `system-user-prompt` and `system-user-list` did not exist. They now use the round `system-switch-user` of the other buttons (hibernate, sleep, restart, shut down).

## [1.0.0-3] - 2026-11-14

### Fixed

- The Thunar icon (`thunar`, `Thunar`, `org.xfce.thunar`, `thunar-filemanager`) kept the pale orange of Tela (`#e39b57`). It now has the Soplos folder design: the front with the gradient from `#ff7d2e` to `#fec431` and the back in `#c73c18`.
- The Desktop icon (`user-desktop`, `desktop`) had a white layer at 25% over the Soplos gradient, so it looked pale beside the other folders. The layer is removed.
- Place icons that sidebars and menus show at 16, 22 and 24 px (open folder, recent, bookmarks, favorites, saved searches, network, shared folders, identity) had a gray copy in `actions` with the same name, which can be picked instead of the colored one. The gray copies are now links to the colored ones. The toolbar buttons (home, back, reload...) stay monochrome.
- Device icons at 16, 22, 24 and 32 px (drives, USB, memory cards, optical media, keyboard, mouse, cameras, headphones, speakers, printers, scanner, phones, tablet, laptop, TV, modem, network, UPS...) were the gray glyphs of Tela. They are now links to their colored versions. Encrypted and root drives use the colored drive, the iPod the colored media player and the radio the colored radio.
- The brand folders at 16 px (Apple, CD, cloud, GitHub, GitLab, GNOME, Google Drive, Linux, mail cloud, MEGA, MEOcloud, pCloud, Steam, torrent, VirtualBox, Wi-Fi, Wine, Yandex Disk) were gray glyphs. They now use the Soplos folder.
- The mail Sent folder (`mail-sent`) used the gray send button. It now uses the colored mail folder.
- The shut down, restart, suspend, hibernate, log out, switch user and lock buttons at 32 px, shown large in the Xfce log out dialog, were gray. They now use the colored ones, as do `printer`, `applications-other`, `applications-all` and `drive-removable-media-usb` at 32 px.

## [1.0.0-2] - 2026-11-14

### Fixed

- The Computer entry in the sidebar of Thunar was a gray outline. At 24 px the theme had a gray `computer` in `places` besides the colored one of Kora Soplos in `devices`. The `computer` of `places` at 24 px is now a link to the colored one. The fault came from Tela ubuntu.

## [1.0.0-1] - 2026-11-14

### Fixed

- The trash in the sidebar of Dolphin and other file managers was a gray outline among orange folders. At 22 and 24 px the theme had a gray `user-trash` in `actions` besides the colored one in `places`, and `actions` is looked up first. The `user-trash` and `user-trash-full` icons of `actions` at 22 and 24 px are now links to the colored ones, as the 16 px special folders. The fault came from Tela ubuntu.

## [1.0.0] - 2026-11-12

### Added

- First release. Three icon themes for Soplos Linux built on the Tela ubuntu variant: `tela-soplos`, `tela-soplos-dark` and `tela-soplos-light`.
- Soplos icons: `distributor-logo`, `distributor-logo-soplos`, `start-here-soplos`, `soplos-launcher`, Ghostty (`com.mitchellh.ghostty`), the `control-centre` panel icon and `application-x-soplos-theme` for the `.sth` files of Soplos Theme Manager.
- Debian package `tela-soplos-icons`, architecture `all`.

### Removed

- The color variants of the folder, home, desktop and network icons of Tela (blue, brown, green, grey, orange, pink, purple, red, yellow, black, cyan, magenta, violet and custom, `*-folder*`, `folder-<color>`), and the links that pointed to them. Soplos has a single folder color.

### Changed

- The 16 px icons of the special folders (home, desktop, trash, documents, downloads, pictures, music, videos, templates and the remote and network folders) were flat gray glyphs, so file manager sidebars such as Thunar's mixed gray and colored icons. They now use the same orange folder icons as the other sizes. The `computer` and `drive-harddisk` icons are the colored ones of Kora Soplos.
- New folder design, so the themes are not mistaken for Tela ubuntu: the orange body is a gradient from Soplos orange (`#ff7d2e`) to yellow (`#fec431`), and the back tab is dark orange (`#c73c18`), as in Kora Soplos. It applies to every folder, home and desktop icon.
- Accent color changed from Tela blue (`#4285f4`, `#5294e2`) and Ubuntu orange (`#fb8441`) to Soplos orange (`#ff7d2e`) in folders, panel, action, status and symbolic icons. Every folder icon is Soplos orange. The blue of about 130 system app icons (settings, preferences, system tools) is shifted to orange. The icons of third-party apps keep their colors.
- The dark and light variants inherit from `tela-soplos`, which holds the shared icons.
