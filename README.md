# HN-2022-Du_Guesclin
dépôt projet de groupe - eScriptorium - Le Livre des faits de messire Bertrand du Guesclin
====

BLABLABLA SUR LE PROJET

Le passage concerné occupe les folios 1 (carré noir) à 8 (*bretaigne*), soit 16 colonnes, à savoir:
- [folio 2v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f18)
- [folio 3r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f19)
- [folio 3v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f20)
- [folio 4r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f21)
- [folio 4v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f22)
- [folio 5r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f23)
- [folio 5v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f24)
- [folio 6r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f25)
- [folio 6v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f26)

# Contenu du dépôt
- `css/` contient la feuille de style de `caracteres.html`
- `csv/` contient la table des caractères
- `documentsDeTravail/` contient les transcriptions utilisées pour réaliser les `veriteTerrain/` du projet
- `img/` contient des images pour l'illustration de `caracteres.html` et de `normesTranscription.md`
- `modeles/` : contient les modèles d'entraînement HTR utilisés:
    - `cremma_medieval_bicerin.mlmodel` : le modèle Cremma Mediéval 1.0.0 Bicerin
    - `fineTunEneide2mains_best.mlmodel` : le modèle fineTunEneide
- `py/` contient
    - `caracteres.py` : le script python de génération de `caracteres.html` à partir de `csv/caracteres.csv`
    - `iiifSelection.py` : le script python de génération dans un terminal de l'URL d'une zone d'intérêt dans une image IIIF
- `rapport/` contient le rapport du projet au format `.pdf`, ainsi qu'un sous-dossier contenant les fichiers-sources `.tex` et `.bib`. 
- `tutos/` contient des outils de contribution au projet :
    - `tuto-iiif.md` : pour générer l'URL d'une zone d'intérêt dans une image IIIF
    - `tutoJunicode.md` : pour installer la police de caractères Junicode
    - `tuto-segmentation.mp4` : pour segmenter un folio dans eScriptorium
    - `tuto-trasncription.tar.xz` : pour transcrire un folio dans e-Scriptorium
- `veriteTerrain/` contient les vérités terrain du projet : fichiers `.xml` et images `.jpg`
- `CITATION.cff` : informations de citation
- `caracteres.html` : table des caractères d'après le manuscrit du projet ; elle propose une liste des formes de lettres et les solutions d'encodage des cas complexes, notamment les abréviations
- `clavier-virtuel-decameron.json` : clavier virtuel à importer dans e-Scriptorium avant de commencer la transcription ; donne accès à la plupart des caractères spéciaux utilisés
- `normesTranscription.md` : description détaillée des normes de transcription employée dans le projet

# Auteurs
Ce projet a été réalisé par :

- Sébastien Biay
- Victor Boby
- Zoé Cappe
- Kristina Konstantinova

 dans le cadre du master TNAH "Technologies Numériques Appliquées à l'Histoire" de l'[Ecole Nationale des Chartes](https://www.chartes.psl.eu/)

- [folio 2v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f18)
- [folio 3r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f19)
- [folio 3v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f20)
- [folio 4r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f21)
- [folio 4v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f22)
- [folio 5r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f23)
- [folio 5v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f24)
- [folio 6r](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f25)
- [folio 6v](https://gallica.bnf.fr/view3if/ga/ark:/12148/btv1b7100018t/f26)
