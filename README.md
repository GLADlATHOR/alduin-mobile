# Alduin mobile

Alduin est un assistant qui tourne **sur le téléphone** (Android) : son modèle d'IA est téléchargé une fois, puis il
répond sans serveur. Discussion écrite ou à la voix, compagnon par appui long sur le bouton latéral, agenda, minuteur,
météo, recherche web, lecture de photos (tableaux, horaires), mémoire de ce que tu lui demandes de retenir, widgets.

## Installer

1. Sur le téléphone, ouvre la [dernière version](https://github.com/GLADlATHOR/alduin-mobile/releases/latest) et
   télécharge **Alduin-mobile.apk**.
2. Ouvre le fichier et autorise l'installation (Android le demande pour une appli qui ne vient pas du Play Store).
3. Au premier lancement, Alduin conseille un modèle selon la mémoire du téléphone et le télécharge (1 à 4 Go, en Wi-Fi
   de préférence).

## Ce qu'il faut

- Android 8 ou plus récent, processeur 64 bits (arm64).
- 8 Go de mémoire au minimum ; 12 Go conseillés pour le modèle le plus complet (Gemma 4 E4B).

## Ce qui passe par internet

Le modèle répond sur le téléphone : les discussions restent sur le téléphone. Internet ne sert que quand c'est utile :
téléchargement du modèle (Hugging Face), recherche web (DuckDuckGo, Wikipédia et les pages lues), météo (Open-Meteo), et une
vérification par jour de la dernière version ici.

## Mises à jour

L'appli regarde une fois par jour s'il existe une nouvelle version sur cette page et propose de l'installer
(Android demande confirmation).
