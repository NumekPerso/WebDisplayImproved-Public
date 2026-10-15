# WebDisplays Improved — public downloads

This repository hosts the **Chromium runtime** used by the WebDisplays Improved Minecraft mod
(screens that show web pages, images and GIFs in the world). It contains binaries only.

## Why the mod downloads Chromium

Web pages are rendered by Chromium (the engine of Google Chrome). It is about 175 MB per
system, too big to ship inside the mod jar, so the mod downloads it **once, and only after
the player agrees** in game. Without it, image and GIF screens still work.

- Files: see [Releases](https://github.com/NumekPerso/WebDisplayImproved-Public/releases)
  (`natives-*` tags, one archive per system).
- Every archive is checked against a SHA-256 checksum built into the mod before it is used.
- Installed in the game folder, under `webdisplays/natives`. Delete that folder to remove it.

## Licenses

The archives contain `jcef.dll`/`jcef_helper` built from a modified copy of
[java-cef](https://github.com/chromiumembedded/java-cef) and the
[Chromium Embedded Framework](https://bitbucket.org/chromiumembedded/cef), both under the
BSD license. The license texts and the Chromium credits are in the `licenses` folder of
each archive.

---

# WebDisplays Improved — téléchargements publics

Ce dépôt héberge **Chromium** pour le mod Minecraft WebDisplays Improved (écrans de pages
web, d'images et de GIF). Il ne contient que des binaires.

Les pages web sont affichées par Chromium (le moteur de Google Chrome), environ 175 Mo par
système : trop gros pour le jar du mod. Le mod le télécharge **une seule fois, et seulement
avec l'accord du joueur** en jeu. Sans lui, les écrans d'images et de GIF fonctionnent.
Chaque archive est vérifiée (SHA-256) avant utilisation et s'installe dans le dossier du jeu,
sous `webdisplays/natives`.
