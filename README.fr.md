# SecretVideo

**Un lecteur dédié pour regarder les vidéos de nombreux sites — et les enregistrer quand vous en avez besoin.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de divergence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-1.3.2-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/secretvideo?lang=fr)

![Capture d'écran de SecretVideo](images/secretvideo-en.webp)

## Présentation

SecretVideo est un lecteur de type navigateur conçu pour les sites de vidéos. Choisissez un site sur l'écran d'accueil et il s'ouvre aussitôt ; lorsque vous passez une vidéo en plein écran, elle se transforme en une petite **fenêtre PIP** pour continuer à regarder tout en faisant autre chose.

Lorsque la vidéo que vous regardez peut être enregistrée, un **bouton de téléchargement** apparaît à côté de la barre d'adresse. Un clic l'enregistre dans le format et la qualité choisis — original, MP4 ou MP3. Les sites nécessitant une connexion fonctionnent aussi : connectez-vous une fois dans SecretVideo et la session est conservée.

Le blocage des publicités est activé par défaut, et `Ctrl+P` enregistre la page entière que vous consultez sous forme d'image.

## Fonctionnalités

- **Écran d'accueil des sites** — YouTube, Twitch, TikTok, CHZZK, Netflix, TVING, Wavve, Watcha, Coupang Play et bien d'autres réunis au même endroit. Ajoutez ou modifiez la liste à votre guise.
- **Plein écran → PIP automatique** — passer une vidéo en plein écran la transforme en une petite fenêtre toujours au premier plan. Déplacez-la où vous voulez, redimensionnez-la par les bords.
- **Un bouton de téléchargement qui n'apparaît que lorsqu'il peut fonctionner** — il glisse à l'écran dès qu'une vidéo enregistrable est prête. Il n'apparaît ni pour les publicités ni pour les directs.
- **Format et qualité au choix** — Original / MP4 / MP3, 720p / 1080p / Meilleure qualité.
- **Fenêtre de liste des téléchargements** — vignettes et progression en un coup d'œil, avec une notification Windows à la fin.
- **Large prise en charge des sites** — un moteur de téléchargement très répandu (yt-dlp) est intégré ; pour les sites qu'il ne connaît pas, SecretVideo repère lui-même le fichier en cours de lecture et l'enregistre.
- **Rester connecté** — connectez-vous à un site dans SecretVideo et les vidéos réservées aux membres peuvent aussi être regardées et enregistrées.
- **Blocage des publicités** — uBlock Origin Lite est intégré et s'active ou se désactive depuis le menu.
- **Capture de page entière** — `Ctrl+P` enregistre toute la page, y compris ce qui se trouve sous la ligne de flottaison, en PNG.
- **Mémorise vos fenêtres** — position/taille/état agrandi de la fenêtre principale, position et taille de la fenêtre PIP, position de la liste des téléchargements.

## Téléchargement / Installation

| Paquet | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/secretvideo?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/secretvideo?lang=fr&nosetup) |

SecretVideo peut s'utiliser en version portable : décompressez le ZIP où vous voulez et lancez `SecretVideo.exe`.

**Au premier lancement**, il télécharge les composants nécessaires à l'enregistrement des vidéos (moteur de téléchargement, convertisseur, bloqueur de publicités). Attendez la fin de la fenêtre de progression. Cela ne se produit qu'une fois ; ensuite, il ne retélécharge que si un composant a changé.

## Utilisation

### Le déroulement de base

1. Lancez SecretVideo. L'**écran d'accueil des sites** apparaît. Cliquez sur le site voulu.
2. Parcourez le site et lisez une vidéo comme dans n'importe quel navigateur.
3. Si la vidéo peut être enregistrée, un **bouton de téléchargement** (↓) apparaît à droite de la barre d'adresse. Cliquez dessus et l'enregistrement démarre immédiatement.
4. La fenêtre **Liste des téléchargements** s'ouvre automatiquement et affiche la progression. À la fin, une notification Windows apparaît ; cliquez dessus pour ouvrir le dossier de destination.

Le dossier de destination par défaut est le dossier **Téléchargements** de votre PC. Modifiez-le dans le menu (⋮) → **Paramètres du dossier**, ou ouvrez-le avec **Ouvrir le dossier**.

### La fenêtre

| Commande | Rôle |
|---|---|
| ◀ ▶ | Précédent / Suivant |
| ⟳ / ✕ | Recharger (Arrêter pendant le chargement d'une page) |
| Barre d'adresse | Saisissez une adresse pour y aller, ou des mots pour lancer une recherche |
| ↓ | Bouton de téléchargement — n'apparaît que lorsqu'une vidéo enregistrable est prête |
| ⋮ | Menu |

Le titre de la fenêtre suit le titre de la page. Si un site tente d'ouvrir une nouvelle fenêtre, SecretVideo l'ouvre dans la fenêtre actuelle.

### Comment…

**Enregistrer une vidéo YouTube en MP3**
Menu → **Paramètres du format → MP3**, puis cliquez sur le bouton de téléchargement sur la page de la vidéo. Seul l'audio est téléchargé et converti en MP3. Le réglage de qualité n'a aucun effet sur le MP3.

**Obtenir un fichier lisible sur un téléviseur ou d'autres appareils**
Choisissez **Paramètres du format → MP4**. À résolution égale, SecretVideo privilégie le format H.264, largement compatible, de sorte que le fichier a moins de chances de refuser de se lire sur un lecteur basique ou un téléviseur. **Original** enregistre tel quel ce que fournit le site (fusionné en MP4 si nécessaire).

**Économiser de l'espace, ou obtenir la meilleure qualité**
Sous **Qualité de téléchargement**, choisissez **720p**, **1080p** (par défaut) ou **Meilleure qualité**. 720p et 1080p signifient « jusqu'à cette résolution » : si elle n'est pas disponible, la résolution immédiatement inférieure est utilisée.

**Les téléchargements échouent ou se bloquent souvent**
Essayez **Vitesse de téléchargement → Stable**. Il télécharge un fragment à la fois, ce qui résiste bien à une connexion peu fiable. Si votre connexion est rapide, **Rapide** (plusieurs fragments à la fois) est bien plus véloce. La valeur par défaut est **Normale**.

**Vidéos réservées aux membres nécessitant une connexion**
Connectez-vous au site dans SecretVideo comme vous le feriez normalement. La connexion est conservée : dès lors, les vidéos réservées aux membres se lisent directement et le bouton de téléchargement apparaît chaque fois qu'une vidéo peut être enregistrée.

**Télécharger une playlist entière**
Sur une page de playlist YouTube, cliquez sur le bouton de téléchargement pour télécharger toute la liste, vidéo après vidéo. Les listes **Mix / Radio** générées automatiquement font exception : seule la vidéo que vous regardez est téléchargée.

**Sites où l'on passe d'une vidéo à l'autre en faisant défiler (TikTok et similaires)**
SecretVideo repère la vidéo en cours de lecture même si l'adresse de la page ne change pas ; faites simplement défiler jusqu'à celle qui vous plaît et cliquez sur le bouton de téléchargement.

**Sites de streaming comme CHZZK et Twitch**
Les rediffusions (VOD) et les clips peuvent être enregistrés. **Les directs ne peuvent pas être enregistrés**, et le bouton de téléchargement n'apparaît pas pour eux.

**Continuer à regarder tout en travaillant (PIP)**
Passez une vidéo en **plein écran** et SecretVideo se transforme automatiquement en une petite fenêtre PIP toujours au premier plan.
- **Faites glisser** la fenêtre pour la déplacer.
- Saisissez un **bord** pour la redimensionner.
- Menu **clic droit** : Revenir à la fenêtre normale / Toujours au premier plan activé ou non / Quitter.
- Lorsque le site quitte le plein écran, la fenêtre retrouve sa taille et sa position précédentes.
- La position et la taille de la fenêtre PIP sont mémorisées pour la prochaine fois.
- Si vous ne voulez pas de ce comportement, désactivez Menu → **Activer le PIP en passant en plein écran**. Le plein écran occupera alors tout le moniteur, comme dans un navigateur classique.

**Conserver une page entière sous forme d'image**
Appuyez sur `Ctrl+P`. **La page entière** — pas seulement la partie visible, mais tout ce qui se trouve en dessous — est enregistrée dans le dossier de destination sous un nom comme `SecretVideo-001.png`, et une notification apparaît. Pratique pour conserver des publications, des commentaires ou des écrans sous-titrés.

**Les publicités gênent / un site se comporte mal à cause du blocage**
Le blocage des publicités (uBlock Origin Lite) est activé par défaut. Si un site précis ne fonctionne pas correctement, désactivez-le temporairement dans Menu → **Extensions**.

**Gérer les fichiers téléchargés (fenêtre Liste des téléchargements)**
Ouvrez-la à tout moment via Menu → **Liste des téléchargements**. Chaque ligne affiche une vignette, le titre, la source et l'état (Inactif → Analyse → Réception → Conversion → Terminé), et le fond de la ligne indique la progression.
- **Double-clic** : ouvrir le fichier téléchargé
- **Touche Suppr** : retirer de la liste
- **Clic droit** : Aller à la source / Ouvrir le dossier / Voir le journal / Supprimer
- Fermer la fenêtre ou appuyer sur `Échap` ne fait que la masquer ; les téléchargements continuent.

**Télécharger deux fois la même vidéo**
Si un fichier du même nom existe déjà, il n'est pas écrasé ; un numéro tel que `(1)`, `(2)` est ajouté.

**Modifier l'écran d'accueil des sites**
Utilisez **Edit** sur l'écran d'accueil pour ajouter ou retirer des sites, et **Reset** pour rétablir la liste par défaut. Ne garder que les sites que vous utilisez vraiment rend le démarrage plus rapide.

### Avertissement sur les droits d'auteur

SecretVideo est un outil pour regarder et conserver, à titre personnel, des vidéos que vous êtes en droit d'utiliser. Respectez les conditions d'utilisation et les droits d'auteur de chaque site.

## Configuration

Il n'y a pas de fenêtre de paramètres séparée ; tout se modifie depuis le menu (⋮) et s'enregistre automatiquement.

| Menu | Ce qu'il règle | Par défaut |
|---|---|---|
| Paramètres du dossier / Ouvrir le dossier | Où les fichiers sont enregistrés | Dossier Téléchargements |
| Paramètres du format | Original / MP4 / MP3 | Original |
| Vitesse de téléchargement | Stable / Normale / Rapide | Normale |
| Qualité de téléchargement | 720p / 1080p / Meilleure qualité | 1080p |
| Liste des téléchargements | Afficher ou masquer la fenêtre de liste | S'ouvre seule au démarrage d'un téléchargement |
| Activer le PIP en passant en plein écran | Transformer le plein écran en fenêtre PIP | Activé |
| Extensions | Blocage des publicités activé ou non | Activé |

La langue de l'interface suit la langue d'affichage de Windows (coréen → coréen, toute autre → anglais).

## Configuration requise

- Windows 10 ou Windows 11, **64 bits**
- Microsoft Edge WebView2 Runtime (déjà présent sur Windows 11 et les Windows 10 récents ; l'installateur l'ajoute s'il manque)
- Une connexion Internet (téléchargement des composants au premier lancement, visionnage et enregistrement des vidéos)

## Mises à jour

SecretVideo **ne** se met **pas** à jour tout seul. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page SecretVideo](https://kilho.net/secretvideo). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

**Historique des versions**

| Version | Date | Notes |
|---|---|---|
| 1.3.2 | 2026-09-19 | Extension de blocage des publicités, menu Extensions, téléchargements directs depuis les flux de recommandations, téléchargement des clips, liste des téléchargements plus rapide |
| 1.3.1 | 2026-09-18 | Meilleur enregistrement sur certains sites, options de qualité (720p/1080p/meilleure), correction du redimensionnement PIP |
| 1.3.0 | 2026-09-16 | Mode PIP, fenêtre de liste des téléchargements, notifications de fin, capture de page entière avec `Ctrl+P`, mémorisation de l'état de la fenêtre |
| 1.2.1 | 2026-09-07 | Correction des téléchargements de certains liens Shorts |

## Licence

SecretVideo est un **logiciel gratuit (Freeware)**.

Vous pouvez l'utiliser partout — à la maison, au bureau, dans les écoles et les administrations — et le redistribuer librement sous sa forme non modifiée.

## Liens

- Site web : <https://kilho.net/secretvideo>
- Forum : <https://groups.google.com/g/kilhonet>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
