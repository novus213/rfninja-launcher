***Français** · [English](README.en.md)*

# N.I.N.J.A — Rising Force Online

Launcher officiel du serveur.

## Installation

1. Téléchargez **`RFNinja-setup.zip`** dans la section [Releases](../../releases/latest).
2. Extrayez-le où vous voulez installer le jeu — prévoyez **9 Go** libres.
   Évitez `C:\Program Files` : Windows y restreint l'écriture et le jeu ne
   pourrait plus se mettre à jour.
3. Lancez **`RFNinja.exe`**.

Le client (environ 3,6 Go) se télécharge automatiquement. Si le téléchargement
est interrompu, relancez simplement `RFNinja.exe` : il reprend là où il s'était
arrêté.

## Ensuite

`RFNinja.exe` est aussi le launcher : lancez-le à chaque fois pour jouer. Il
vérifie les mises à jour et les applique avant la connexion.

## En cas de problème

- **Windows ou votre navigateur signale le fichier** : le launcher n'est pas
  signé numériquement, ce qui suffit à déclencher un avertissement. Vous pouvez
  vérifier l'empreinte SHA-256 publiée avec chaque version.
- **Le téléchargement ne démarre pas** : vérifiez que `RFNinja.exe` n'est pas
  bloqué par votre antivirus ou votre pare-feu — il a besoin d'accéder à
  Internet pour installer et mettre à jour le jeu.

## Signaler un problème

Un bug, une idée ? Ouvrez une [issue](../../issues/new/choose). Décrivez ce que
vous avez observé et comment y retomber — une capture d'écran vaut souvent mieux
qu'une longue explication.

Les changements récents sont listés dans le [journal des modifications](CHANGELOG.md).

---

Ce launcher utilise [Qt](https://www.qt.io/) 6.6.1, distribué sous licence LGPL v3.
Les bibliothèques Qt sont fournies telles quelles et peuvent être remplacées par
l'utilisateur.
