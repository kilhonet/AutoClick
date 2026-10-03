# AutoClick

**Un clic automatique gratuit pour Windows qui clique à votre place à l'endroit et à l'intervalle choisis — et qui peut mémoriser une suite d'emplacements à cliquer l'un après l'autre.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/autoclick?lang=fr)

![Écran d'AutoClick](images/autoclick-en.webp)

## Présentation

Certaines tâches obligent à cliquer des dizaines ou des centaines de fois sur le même bouton. AutoClick fait ces clics à votre place.

Choisissez le bouton à presser (gauche, droit ou molette), un clic simple ou double et la fréquence, puis appuyez sur le raccourci (**F3** par défaut) pour démarrer. Appuyez de nouveau sur le même raccourci pour arrêter. Le raccourci fonctionne même quand vous regardez un autre programme : inutile de garder la fenêtre d'AutoClick au premier plan.

S'il faut cliquer plusieurs endroits à tour de rôle et non un seul, utilisez l'**Enregistrement**. Placez la souris sur un endroit et appuyez sur le raccourci (**F4** par défaut) : cette position s'ajoute à la liste, une ligne à la fois. Cochez **Utiliser l'enregistrement** et lancez : AutoClick clique les positions dans l'ordre de la liste.

## Fonctionnalités

- **Clics automatiques** — presse en boucle le bouton gauche, droit ou la molette, en clic simple ou double.
- **Plage d'intervalle** — cliquez à intervalle fixe, par exemple toutes les secondes, ou à un intervalle différent à chaque fois, entre 1 et 3 secondes par exemple. Réglage au centième de seconde.
- **Raccourcis globaux** — démarrez et arrêtez d'une seule touche, même quand un autre programme est au premier plan. Choisissez la combinaison de touches qui vous convient.
- **Enregistrement** — créez un modèle qui clique plusieurs positions dans l'ordre, avec pour chacune son bouton, son type de clic et son intervalle.
- **Modèles enregistrés** — enregistrez la liste dans un fichier et ouvrez-la quand vous en avez besoin. La dernière liste revient telle quelle au lancement suivant.
- **Nombre de répétitions** — s'arrête tout seul après un nombre de clics fixé. Laissez le champ vide pour cliquer jusqu'à ce que vous arrêtiez.
- **Curseur conservé** — après avoir cliqué l'endroit choisi, remet le curseur de la souris là où il était.
- **Avis** — une notification Windows vous prévient au démarrage et à l'arrêt. L'avis de démarrage indique aussi le raccourci pour arrêter.
- **Mode sombre** — suit le mode des applications de Windows (clair ou sombre).
- **8 langues** — coréen · anglais · japonais · chinois · russe · italien · français · espagnol.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Installateur | [Télécharger](https://down.kilho.net/autoclick?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/autoclick?lang=fr&nosetup) |

L'installateur lance AutoClick dès la fin de l'installation. Pour la version portable, décompressez le ZIP et lancez `AutoClick.exe`. Les deux versions ont les mêmes fonctions.

## Utilisation

### Premiers pas

1. Lancez AutoClick.
2. Dans **Paramètres de la souris**, choisissez le bouton à presser (**Souris**), un clic simple ou double (**Clic**) et l'intervalle entre les clics (**Délai**). Au départ, il est réglé pour presser le bouton gauche une fois par seconde.
3. Placez le curseur de la souris sur l'endroit à cliquer.
4. Appuyez sur **F3**. La barre d'état en bas passe à **En cours** et AutoClick commence à cliquer cet endroit à l'intervalle choisi.
5. Quand vous avez fini, appuyez de nouveau sur **F3**. La barre d'état revient à **En attente**.

### Organisation de l'écran

| Élément | Rôle |
|---|---|
| **Accueil** · **Test** · **Faire un don** | Menu du haut. **Test** ouvre une page de test de la souris pour essayer les clics |
| Logo KILHO.net | Ouvre la page d'AutoClick |
| **Paramètres de la souris** | **Souris** (Gauche · Droite · Roue) · **Clic** (Simple · Double) · **Délai** (intervalle entre les clics ; les deux champs forment une plage) |
| **Paramètres des raccourcis** | **Démarrer/Arrêter** (F3 par défaut) · **Ajouter un enregistrement** (F4 par défaut) |
| **Autres paramètres** | **Répéter** · **Position** (Maintenir · Modifier) · **Utiliser les avis** (Activé · Désactivé) |
| Liste **Enregistrement** | Les positions à cliquer, dans l'ordre. Colonnes : **Position** · **Souris** · **Clic** · **Délai** |
| **Utiliser l'enregistrement** | Coché, le lancement clique la liste dans l'ordre |
| **Effacer** · **Ouvrir** · **Enregistrer** | Vide toute la liste / ouvre une liste enregistrée / enregistre la liste dans un fichier |
| Barre d'état | **En attente** ou **En cours** |

### Que faire quand…

**Cliquer sans cesse au même endroit**
Placez le curseur sur l'endroit et appuyez sur **F3** : AutoClick clique sans cesse l'endroit où se trouvait le curseur au démarrage. Avec **Position** sur **Maintenir**, il remet le curseur à sa place après chaque clic ; vous pouvez donc déplacer la souris ailleurs pendant ce temps sans que l'endroit cliqué change.

**Cliquer là où se trouve le curseur**
Réglez **Position** sur **Modifier** : AutoClick clique là où se trouve le curseur au moment de chaque clic, et non à l'endroit du démarrage. Pratique pour déplacer la souris pendant l'exécution et changer ce qui est cliqué.

**Varier un peu l'intervalle à chaque fois**
Saisissez une plage dans les deux champs **Délai**. Par exemple, `00:01.00` et `00:03.00` cliquent à un intervalle différent entre 1 et 3 secondes à chaque fois. Si les deux champs sont identiques, l'intervalle reste le même. Les champs ont la forme `minutes:secondes.centièmes` : il suffit de taper les chiffres dans l'ordre pour qu'ils se placent ; la valeur la plus longue est 99 minutes 59,99 secondes.

**Faut-il remplir les deux champs ?**
Quand vous modifiez le premier champ puis passez à un autre, le second suit le premier. Dès que vous modifiez vous-même le second champ, AutoClick conserve cette valeur ; pour fixer une plage, remplissez donc d'abord le premier champ, puis le second. Si le second est plus petit que le premier, il est remonté à la valeur du premier.

**Cliquer un nombre de fois fixé puis s'arrêter**
Saisissez un nombre dans **Répéter**. AutoClick s'arrête tout seul après ce nombre de clics et, si **Utiliser les avis** est activé, affiche l'avis « L'exécution est terminée : le nombre de répétitions est atteint. » tandis qu'AutoClick clignote dans la barre des tâches. Laissez le champ vide (avec **aucun** en grisé) pour cliquer jusqu'à ce que vous arrêtiez. Un double clic compte pour un.

**Cliquer plusieurs endroits à tour de rôle (Enregistrement)**
1. Choisissez le bouton, le clic et le délai dans **Paramètres de la souris**.
2. Placez le curseur sur le premier endroit et appuyez sur **F4**. Une ligne avec cette position et le bouton, le clic et le délai choisis s'ajoute à la liste **Enregistrement**.
3. Appuyez sur **F4** de la même façon à chaque endroit suivant. Pour un autre bouton ou délai sur une ligne, changez **Paramètres de la souris** avant d'appuyer sur **F4**.
4. Cochez **Utiliser l'enregistrement** et appuyez sur **F3**. AutoClick clique à partir de la première ligne puis, après la dernière, revient à la première. La ligne en cours est mise en évidence dans la liste.

Le **Délai** de chaque ligne est le temps qu'AutoClick attend après avoir cliqué cet endroit avant de passer à la ligne suivante.

**Réordonner les lignes ou en supprimer une seule**
Faites un clic droit sur une ligne de la liste pour **Déplacer vers le haut** · **Déplacer vers le bas** · **Supprimer**. Pour vider toute la liste, cliquez sur **Effacer** puis sur **Oui** dans la confirmation. La liste ne peut pas être modifiée pendant l'exécution : arrêtez d'abord.

**Garder plusieurs modèles et choisir**
Utilisez **Enregistrer** pour garder la liste actuelle dans un fichier, et **Ouvrir** pour la charger au besoin. Un fichier par tâche, c'est pratique. Même sans enregistrer, la liste présente à la fermeture d'AutoClick revient au lancement suivant. Les fichiers d'enregistrement des versions précédentes s'ouvrent tels quels.

**Lire les délais de la liste**
Un intervalle unique s'affiche comme `00:01.00` et une plage comme `01:01.00~05:03.00`, sous la même forme que les champs de saisie. Si une longue plage paraît coupée, survolez-la ou faites glisser la limite entre les en-têtes de colonnes pour élargir la colonne.

**Changer un raccourci**
Cliquez sur un champ de **Paramètres des raccourcis** : il affiche « Appuyez sur une touche ». Appuyez sur la touche voulue, ou sur une combinaison avec **Ctrl** · **Alt** · **Maj** (par exemple **Ctrl+Shift+F3**) : elle est changée et enregistrée aussitôt. Appuyez sur **Échap** dans le champ pour vider ce raccourci (**Aucun**). Choisissez une touche que vos jeux ou autres programmes n'utilisent pas.

**Quand un raccourci entre en conflit avec un autre programme**
Si un autre programme utilise déjà la même touche, AutoClick vous le signale. Changez de touche ou fermez ce programme ; une fois celui-ci fermé, relancer AutoClick réactive votre touche d'origine. Si vous mettez la même touche pour les deux raccourcis, AutoClick indique qu'elle est déjà utilisée par l'autre fonction et la refuse.

**Si vous n'avez pas besoin des avis**
Réglez **Utiliser les avis** sur **Désactivé** : AutoClick n'affiche plus d'avis de démarrage, d'arrêt ou de répétitions terminées. Activé, l'avis de démarrage rappelle comment arrêter, par exemple « Appuyez à nouveau sur le même raccourci pour l'arrêter (F3) » — utile si vous oubliez le raccourci.

**Presser le bouton de la molette**
Choisir **Roue** pour **Souris** presse le bouton de la molette (bouton du milieu) au lieu de faire défiler. À utiliser là où le bouton du milieu a une action, comme ouvrir un lien dans un nouvel onglet du navigateur.

**Essayer avant de commencer**
Cliquez sur **Test** en haut pour ouvrir dans le navigateur une page de test de la souris qui compte les clics et doubles clics des boutons gauche, molette et droit. Vous pouvez changer le bouton, le clic et le délai et vérifier d'abord que les clics se font comme prévu.

**Changer les réglages pendant l'exécution**
Pendant l'exécution, les champs sont verrouillés pour éviter tout changement accidentel. Arrêtez avec **F3**, faites vos modifications et appuyez de nouveau sur **F3**.

**Le relancer alors qu'il est déjà ouvert**
Une seule copie d'AutoClick peut tourner. Le relancer n'en ouvre pas une nouvelle : la fenêtre déjà ouverte passe au premier plan. Le titre de la fenêtre affiche la version actuelle.

## Configuration

Il n'y a pas de fenêtre de réglages à part. Les raccourcis, **Position** et **Utiliser les avis** sont mémorisés dès que vous les changez, et la liste est enregistrée à la fermeture d'AutoClick et revient la fois suivante. AutoClick suit de lui-même :

| Élément | Suit |
|---|---|
| Langue | Les paramètres régionaux de Windows (anglais si la langue n'est pas prise en charge) |
| Couleurs | Le mode des applications de Windows (clair ou sombre) — le changement s'applique aussitôt pendant qu'AutoClick est ouvert |

## Configuration requise

- Windows 10 · Windows 11 (64 bits)
- Aucun droit administrateur n'est nécessaire.
- Aucun autre composant à installer.
- La connexion Internet ne sert qu'aux avis de nouvelle version. Toutes les fonctions marchent sans connexion.

## Mises à jour

AutoClick ne se met **pas** à jour tout seul. Au lancement, il vérifie s'il existe une nouvelle version et affiche un avis ; cliquer sur **[Oui]** ouvre la page de téléchargement et ferme le programme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page d'AutoClick](https://kilho.net/autoclick). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

AutoClick est un **gratuiciel** (freeware). Utilisez-le gratuitement et sans restriction partout — au travail, à la maison, dans les administrations ou à l'école — et redistribuez-le librement.

## Liens

- Site web : <https://kilho.net/autoclick>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
