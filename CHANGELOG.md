# Changelog

All notable changes to Tela Soplos Icons are documented in this file.

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
