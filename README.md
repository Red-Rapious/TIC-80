[![Build Status](https://travis-ci.org/nesbox/TIC-80.svg?branch=master)](https://travis-ci.org/nesbox/TIC-80)
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

