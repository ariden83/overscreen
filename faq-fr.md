---
title: OverScreen — FAQ
---

# <img src="graphics/picto-title.png" alt="" align="absbottom" width="50" height="48" style="vertical-align: bottom;">&nbsp;&nbsp;&nbsp;OverScreen — Questions fréquentes

[Politique de confidentialité](fr.md) · [Conditions d'utilisation](terms-fr.md) · **FAQ** · [Mentions légales](legal-fr.md) · [English version](faq.md)

## Qu'est-ce qu'OverScreen ?

OverScreen enregistre les touchers et glissements que vous faites dans une application et les rejoue, à votre demande ou automatiquement quand une zone de l'écran que vous avez choisie (un « repère ») apparaît. Il fonctionne comme un panneau flottant par-dessus vos autres applications.

## Comment l'activer ?

Ouvrez OverScreen, lisez l'explication sur le service d'accessibilité et touchez **Accepter et continuer**. Android ouvre alors ses réglages d'accessibilité : choisissez **Applications installées** (ou **Services installés**) > **OverScreen** et activez-le. Le panneau flottant apparaît par-dessus vos applications.

## Le service OverScreen est grisé dans les réglages d'accessibilité

Android restreint les services d'accessibilité des applications qui n'ont pas été installées depuis une boutique. Ouvrez **Paramètres > Applications > OverScreen**, touchez le menu (trois points) et choisissez **Autoriser les paramètres restreints**, puis réactivez le service.

## Le panneau flottant a disparu

- Le téléphone était verrouillé : rien n'est affiché tant qu'il l'est, le panneau revient après le déverrouillage.
- Android a arrêté le service pour économiser la batterie : dans OverScreen, touchez **Batterie : ne pas restreindre OverScreen**, puis réactivez le service dans les réglages d'accessibilité.

## Comment enregistrer et rejouer une séquence ?

Dans le panneau, onglet **Séquences** : touchez **Créer**, utilisez l'application comme d'habitude, puis touchez **Arrêter l'enregistrement**. Cochez la séquence et touchez **Lancer** pour la rejouer. Le picto de répétition à côté choisit le mode de lecture : en boucle, une fois à chaque apparition du repère, ou une fois.

## Qu'est-ce qu'un repère, et pourquoi le mien ne se déclenche-t-il pas ?

Un repère est une petite zone de l'écran qu'OverScreen surveille ; quand elle apparaît, sa séquence démarre. S'il ne se déclenche pas :

- il ne fonctionne que dans l'application, et sur la taille et l'orientation d'écran, où il a été créé ;
- la zone bouge ou change légèrement de teinte : augmentez sa tolérance verticale ou sa tolérance de couleur dans l'éditeur de repère ;
- le repère doit être coché (onglet Repères, puis **Lancer**), ou faire partie d'une liste cochée dans **Actions suivies** ;
- le bouton d'arrêt recouvre peut-être le repère : déplacez-le en le faisant glisser.

## Comment obtenir des suggestions de repères ?

Quand vous créez un repère, cochez une case sur la carte de visée en haut de l'écran. Dans une application, **Détecter les éléments cliquables** entoure les éléments que l'application décrit à Android. Dans un jeu, qui ne décrit rien, deux cases sont proposées, et une seule peut être cochée : **Détecter les textes** lit le texte affiché, et **Détecter les éléments cliquables** lance une analyse d'image par IA (OverScreen Pro). Touchez un carré pour le cocher, puis créez son repère. La version gratuite crée un repère suggéré à la fois ; Pro en crée plusieurs d'un coup.

## Pourquoi l'analyse d'image prend-elle environ une minute et demande-t-elle 5 Go de RAM ?

L'analyse d'image tourne entièrement sur votre téléphone, hors ligne, avec un modèle inclus dans l'application : elle prend environ une minute sur un téléphone de milieu de gamme et demande beaucoup de mémoire, c'est pourquoi elle n'est proposée que sur les téléphones d'au moins 5 Go de RAM. Vous pouvez continuer à viser à la main pendant ce temps. **Détecter les textes** est bien plus rapide et fonctionne sur tous les téléphones.

## Que signifient les petits badges sur les vignettes des repères ?

Ils indiquent comment un repère est reconnu. Un repère de texte est reconnu par son texte, et un repère d'élément cliquable par l'élément de l'application à son emplacement ; pour eux, la vignette n'est qu'indicative. Les repères sans badge sont reconnus par leurs pixels.

## L'IA ou la reconnaissance de texte envoient-elles quelque chose ?

Non. Les deux tournent sur votre téléphone, avec des modèles inclus dans l'application, et OverScreen n'a pas accès à Internet. Les captures d'écran sont analysées sur le téléphone puis supprimées.

## Pourquoi rien ne se passe sur l'écran de verrouillage ?

C'est voulu : OverScreen n'agit jamais tant que le téléphone est verrouillé, pour qu'il ne puisse pas servir à contourner l'écran de verrouillage. Tout reprend après le déverrouillage.

## Que comprend la version gratuite ?

La version gratuite permet d'utiliser 3 séquences, 1 repère et une liste par application, avec le lancement manuel, la surveillance, tous les modes de lecture et les suggestions de repères (éléments cliquables d'une application, textes d'un jeu), un repère à la fois. OverScreen Pro, un achat unique disponible via Google Play, lève ces limites et ajoute l'édition des séquences, les actions automatiques, la sauvegarde, l'analyse d'image par IA des jeux et la création de plusieurs repères suggérés d'un coup.

## Comment transférer mes séquences sur un nouveau téléphone ?

Avec la sauvegarde (fonction Pro) : en bas de l'écran principal d'OverScreen, **Exporter** écrit un fichier à l'endroit de votre choix, et **Importer** le relit sur l'autre téléphone. Les repères ne fonctionnent que sur un écran de même résolution.

## Puis-je utiliser OverScreen dans des jeux ?

OverScreen fait ce que vous feriez vous-même, mais certaines applications et certains jeux interdisent l'automatisation dans leurs conditions d'utilisation. Vérifiez-les avant d'automatiser une application : vous êtes responsable de l'usage que vous faites d'OverScreen (voir les [conditions d'utilisation](terms-fr.md)).

## OverScreen collecte-t-il mes données ?

Non. OverScreen n'a pas accès à Internet et ne collecte aucune donnée ; tout reste sur votre téléphone. Voir la [politique de confidentialité](fr.md).

## Comment vous contacter ?

**ariden.apps@gmail.com**
