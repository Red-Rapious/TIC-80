[![Build Status](https://travis-ci.org/nesbox/TIC-80.svg?branch=master)](https://travis-ci.org/nesbox/TIC-80)
[![Build status](https://ci.appveyor.com/api/projects/status/1pflw77cjd8mqggb/branch/master?svg=true)](https://ci.appveyor.com/project/nesbox/tic-80)

![TIC-80](https://tic.computer/img/logo64.png)
**TIC-80 TINY COMPUTER** - [https://tic.computer/](https://tic.computer/)

# À propos
TIC-80 est une fantasie console **GRATUITE** et **OPEN SOURCE** pour créer, jouer et partager des petits jeux.

With TIC-80 you get built-in tools for development: code, sprites, maps, sound editors and the command line, which is enough to create a mini retro game.

Games are packaged into a cartridge file, which can be easily distributed. TIC-80 works on all popular platforms. This means your cartridge can be played in any device.

To make a retro styled game, the whole process of creation and execution takes place under some technical limitations: 240x136 pixel display, 16 color palette, 256 8x8 color sprites, 4 channel sound, etc.

![TIC-80](https://user-images.githubusercontent.com/1101448/29687467-3ddc432e-8925-11e7-8156-5cec3700cc04.gif)

### Features
- Multiple programming languages: [Lua](https://www.lua.org),
  [Moonscript](https://moonscript.org),
  [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript),
  [Wren](http://wren.io/), and [Fennel](https://fennel-lang.org).
- Games can have mouse and keyboard as input
- Games can have up to 4 controllers as input (with up to 8 buttons, each)
- Built-in editors: for code, sprites, world maps, sound effects and music
- An aditional memory bank: load different assets from your cartridge while your game is executing

# Binary Downloads
You can download compiled versions for the major operating systems directly from our [releases page](https://github.com/nesbox/TIC-80/releases).

# Pro Version
To help support TIC-80 development, we have a [PRO Version](https://nesbox.itch.io/tic).
This version has a few additional features and binaries can only be downloaded on [our Itch.io page](https://nesbox.itch.io/tic).

For users who can't spend the money, we made it easy to build the pro version from the source code.

### Pro features

- Save/load cartridges in text format, and create your game in any editor you want, also useful for version control systems.
- Even more memory banks: instead of having only 1 memory bank you have 8.
- Export your game without editors, and then publish it to app stores (WIP).

# Community
You can play and share games, tools and music at [tic.computer](https://tic.computer/play).[![Build Status](https://travis-ci.org/nesbox/TIC-80.svg?branch=master)](https://travis-ci.org/nesbox/TIC-80)
[![Build status](https://ci.appveyor.com/api/projects/status/1pflw77cjd8mqggb/branch/master?svg=true)](https://ci.appveyor.com/project/nesbox/tic-80)

![TIC-80](https://tic.computer/img/logo64.png)
**TIC-80 TINY COMPUTER** - [https://tic.computer/](https://tic.computer/)

# À propos
TIC-80 est une fantasie console **GRATUITE** et **OPEN SOURCE** pour créer, jouer et partager des petits jeux.

Avec TIC-80 vous avez un environnement de développement intégré: code, sprites, cartes, éditeurs de son et la ligne de commande, ce qui est assez pour créer des petits jeux rétros.

Les jeux sont rangés des dans cartouches, qui peuevnt être facilement distribuées. TIC-80 fonctionne avec toutes les plateformes populaires. Cela signifie que votre cartouche peut être jouée sur n'importe quel appareil.

Pour faire un jeu au style rétro, tout le processus de création et d'exécution prend place dans certaines limitations techniques: 240x136 pixels d'affichage, une palette de 16 couleurs, 256 8x8 sprites colorés, 4 cannaux de son, etc.

![TIC-80](https://user-images.githubusercontent.com/1101448/29687467-3ddc432e-8925-11e7-8156-5cec3700cc04.gif)

### Fonctionnalitées
- Plusieurs langages de programmation: [Lua](https://www.lua.org),
  [Moonscript](https://moonscript.org),
  [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript),
  [Wren](http://wren.io/), et [Fennel](https://fennel-lang.org).
- Les jeux peuvent avoir des entrées souris et clavier
- les jeux peuvent avoir jusqu'à 4 manettes comme entrée (avec jusqu'à 8 boutons chacun)
- Editeurs intégrés: pour le code, les sprites, les cartes, les effets sonores et la musique
- Une mémoire additionnelle: chargez différents assets de votre cartouche quand le jeu s'exécute

# Téléchargements binaires
Vous pouvez téléchargez des versions compilées pour les sytèmes d'exploitations majeurs directement depuis notre [page de versions](https://github.com/nesbox/TIC-80/releases).

# Version pro
Pour aider le developpement de la TIC-80, nous avons une [Version PRO](https://nesbox.itch.io/tic).
Cette version a plusieurs fonctionnalitées additionnelles et ne peut être téléchargée que depuis [notre page Itch.io](https://nesbox.itch.io/tic).

Pour les utilisateurs n'ayant pas d'argent, Nous avons rendu facile la compilation depuis le code source.

### Version PRO

- Sauvegardez/chargez des cartouches en format texte, et créez vos jeux dans l'éditeur que vous voulez, également utile pour les versions de contrôle du système.
- Encore plus de mémoire additionnelle: au lieu d'en avoir 1, vous en avez 8.
- Exportez vos jeux sans éditeurs, et publiez les dans les magasins (WIP).

# Communautée
Vous pouvez jouer et partager vos jeux, outils et musiques sur [tic.computer](https://tic.computer/play).

La communautée discute aussi sur [le chat Discord](https://discord.gg/DkD73dP).

# Contribution
Vous pouvez contribuer enreportant un bug ou en demendant une nouvelle fonctionnalité sur [cette page](https://github.com/nesbox/tic.computer/issues).
Gardez en tête de respecter notre [Code de Conduite](https://github.com/nesbox/TIC-80/blob/master/CODE_OF_CONDUCT.md) lorsque vous engagez une discussion.

Vous pouvez aussi contribuer en traduisant ou améliorant notre [wiki](https://github.com/nesbox/tic.computer/wiki).
Le [wiki](https://github.com/nesbox/tic.computer/wiki) contient la documentation de la TIC-80, des astuces de developpement et des tutoriels.

# Instructions de compilation

## Windows
### avec Visual Studio 2017
- installez `Visual Studio 2017`
- installez `git`
- lancez la commande suivante dans `cmd`
```
git clone --recursive https://github.com/nesbox/TIC-80
cmake -G "Visual Studio 15 2017 Win64"
```
- ouvrez `TIC-80.sln` et compilez
- amusez-vous :)

### avec MinGW
- installez `mingw-w64` (http://mingw-w64.org) et ajoutez le chemin `.../mingw/bin` au *System Variables Path*
- installez `git`
- installez `cmake` (https://cmake.org)
- lancez la commande suivante dans le `terminal`
```
git clone --recursive https://github.com/nesbox/TIC-80
cd TIC-80
cmake -G "MinGW Makefiles"
mingw32-make -j4
```

## Linux 
### Ubuntu 14.04
lancez la commande suivante dans le Terminal:
```
sudo apt-get install git cmake libgtk-3-dev libgles1-mesa-dev libglu-dev -y
git clone --recursive https://github.com/nesbox/TIC-80 && cd TIC-80
cmake . && make -j4
```

pour installer le dernier CMake:
```
wget "https://cmake.org/files/v3.12/cmake-3.12.0-Linux-x86_64.sh"
sudo sh cmake-3.12.0-Linux-x86_64.sh --skip-license --prefix=/usr
```

### Ubuntu 18.04

lancez la commande suivante dans le Terminal:
```
sudo apt-get install git cmake libgtk-3-dev libglvnd-dev libglu1-mesa-dev freeglut3-dev -y
git clone --recursive https://github.com/nesbox/TIC-80 && cd TIC-80
cmake . && make -j4
```

## Mac
installez `Command Line Tools for Xcode` et le gestionnaire de package `brew`

lancez la commande suivante dans le Terminal:
```
brew install git cmake
git clone --recursive https://github.com/nesbox/TIC-80
cd TIC-80
cmake . && make -j4
```

## iOS / tvOS
Vous pouvez trouver la version iOS/tvOS ici:
- 0.60.3: https://github.com/brunophilipe/TIC-80
- 0.45.0: https://github.com/CliffsDover/TIC-80


The community also hangs out and discusses on [Discord chat](https://discord.gg/DkD73dP).

# Contributing
You are can contribute by issuing a bug or requesting a new feature on our [issues page](https://github.com/nesbox/tic.computer/issues).
Keep in mind when engaging on a discussion to follow our [Code of Conduct](https://github.com/nesbox/TIC-80/blob/master/CODE_OF_CONDUCT.md).

You can also contribute by reviewing or improving our [wiki](https://github.com/nesbox/tic.computer/wiki).
The [wiki](https://github.com/nesbox/tic.computer/wiki) holds TIC-80 documentation, code snippets and game development tutorials.

# Build instructions

## Windows
### with Visual Studio 2017
- install `Visual Studio 2017`
- install `git`
- run following commands in `cmd`
```
git clone --recursive https://github.com/nesbox/TIC-80
cmake -G "Visual Studio 15 2017 Win64"
```
- open `TIC-80.sln` and build
- enjoy :)

### with MinGW
- install `mingw-w64` (http://mingw-w64.org) and add `.../mingw/bin` path to the *System Variables Path*
- install `git`
- install `cmake` (https://cmake.org)
- run following commands in `terminal`
```
git clone --recursive https://github.com/nesbox/TIC-80
cd TIC-80
cmake -G "MinGW Makefiles"
mingw32-make -j4
```

## Linux 
### Ubuntu 14.04
run the following commands in the Terminal
```
sudo apt-get install git cmake libgtk-3-dev libgles1-mesa-dev libglu-dev -y
git clone --recursive https://github.com/nesbox/TIC-80 && cd TIC-80
cmake . && make -j4
```

to install the latest CMake:
```
wget "https://cmake.org/files/v3.12/cmake-3.12.0-Linux-x86_64.sh"
sudo sh cmake-3.12.0-Linux-x86_64.sh --skip-license --prefix=/usr
```

### Ubuntu 18.04

run the following commands in the Terminal
```
sudo apt-get install git cmake libgtk-3-dev libglvnd-dev libglu1-mesa-dev freeglut3-dev -y
git clone --recursive https://github.com/nesbox/TIC-80 && cd TIC-80
cmake . && make -j4
```

## Mac
install `Command Line Tools for Xcode` and `brew` package manager

run the following commands in the Terminal
```
brew install git cmake
git clone --recursive https://github.com/nesbox/TIC-80
cd TIC-80
cmake . && make -j4
```

## iOS / tvOS
You can find iOS/tvOS version here 
- 0.60.3: https://github.com/brunophilipe/TIC-80
- 0.45.0: https://github.com/CliffsDover/TIC-80
