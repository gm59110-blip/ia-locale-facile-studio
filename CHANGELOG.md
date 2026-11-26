# Journal des modifications

Toutes les versions d'IA Locale Facile Studio. Le fichier à télécharger s'appelle toujours
`IA-Locale-Facile-Studio.zip` : le lien
<https://github.com/gm59110-blip/ia-locale-facile-studio/releases/latest/download/IA-Locale-Facile-Studio.zip>
donne toujours la dernière version.

## 1.0.1 (26 novembre 2026)

### Cartes graphiques
- **Plusieurs cartes NVIDIA** : toutes les cartes sont maintenant détectées, pas seulement la première. Une machine
  à 2 RTX 5090 s'affiche « 2x RTX 5090 (2×32 Go) ». Les images et les vidéos se calculent sur la première carte, et
  le chat répartit le modèle de langue sur toutes les cartes.
- **Mémoire unifiée (NVIDIA GB10, DGX Spark)** : quand `nvidia-smi` ne donne pas de mémoire vidéo (« N/A »), l'appli
  compte la mémoire partagée de la machine au lieu de conclure qu'il n'y a pas de carte NVIDIA.
- **Grosses cartes (Premium)** : l'installation propose d'office des modèles plus capables selon la mémoire vidéo :
  Z-Image Turbo pour les images à partir de 16 Go, LTX-2.5 pour la vidéo à partir de 24 Go (et 32 Go de mémoire vive).
  L'édition gratuite garde FLUX.2 Klein 4B et Wan 2.2 5B, dans la meilleure déclinaison qui tient dans la carte.

### Création
- Le prompt est traduit dès l'envoi, pendant que la carte calcule la création précédente : les files d'attente
  avancent plus vite.

### Téléchargement
- Le fichier de la version s'appelle désormais `IA-Locale-Facile-Studio.zip`, sans numéro de version, pour que les
  liens de téléchargement ne changent plus d'une version à l'autre.

## 1.0.0 (20 novembre 2026)
- Première version publique.
