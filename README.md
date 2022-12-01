# Scoobyland

Bienvenue sur **Scoobyland**, le serveur où se retrouvent tous les clebs de notre beau groupe.
Ce répo a pour but de regrouper toutes les ressources nécessaires afin d'accéder au serveur et que tout le monde soit sur un pied d'égalité en terme de textures, shaders, mods...
Suivez les étapes suivantes **dans l'ordre**, une fois celles-ci complétées, vous pourrez rejoindre le serveur sans encombre.

## 1. Installer Fabric 1.19 sur son client minecraft

Fabric est primordial sur le serveur car il permet d'ajouter des mods -indépendants des plugins présents sur le serveur- à son client minecraft.
Afin d'installer Fabric, il suffit de télécharger le [fichier source](https://github.com/Clement-picot6/minecraft/blob/main/utils/) et de cliquer dessus. Une interface s'ouvrira, il suffira de sélectionner **Install client** et valider.

![Fabric installer](https://img001.prntscr.com/file/img001/hQRfBiONSOSloMbFn6drRA.jpeg)


## Installer les mods sur son client minecraft
Trois mods sont prérequis pour lancer le serveur.
1. Iris : c'est un mod permet d'optimiser les performances de son client minecraft DRASTIQUEMENT lorsqu'on utilise les shaders. Je suis par exemplé passé de 30FPS à 170FPS constants. Et en plus c'est français 🐓
2. Sodium : C'est un moteur de rendu open-source qui fonctionne avec Iris. Il augmente énormément les perfs !
3. Simple Voice Chat : c'est un vocal de proximité (normalement tout le monde connait j'ai pas besoin d'expliquer).

Pour installer ces mods, appuyez simultanément sur **Win + R** et rentrez l'URL suivante :

    %appdata%/.minecraft/mods
Tout ce que vous avez à faire, c'est de glisser les trois fichiers du [dossiers mods du répo github](https://github.com/Clement-picot6/minecraft/tree/main/mods) dans le dossier mods de votre client minecraft.


## Sélectionner le bon profil sur son client minecraft

Après avoir installé Fabric, un nouveau profil a été créé sur votre client minecraft. Il est **primordial** de lancer le jeu avec ce profil, sinon **le serveur ne vous laissera pas rentrer**.

![profil Fabric](https://img001.prntscr.com/file/img001/EhPPK7odSfGWpfJs2iyNrw.jpeg)

## Ajouter le ressourcepack
Lancez votre jeu (**profil Fabric**) et rendez-vous dans l'onglet **Options > Ressource Packs**. Cliquez sur **Open Pack Folder** et glissez y **Remodeled-Minecraft1.19.5.zip**.
Assurez vous ensuite de bien sélectionner le ressourcepack avant de valider. Vous devriez avoir quelque chose comme ceci :
![ressourcepack](https://img001.prntscr.com/file/img001/9a0oLoD6QMKoh6_zCvFpGg.jpeg)

## Ajouter les shaders

Même principe que pour le ressourcepack, sauf que les shaders se situent dans l'onglet **Options > Video Settings > Shader Packs**. Encore une fois, ouvrez le dossier des Shaders et glissez y le dossier SEUS-Renewed-v1.0.1.zip **ET** le fichier SEUS-Renewed-v1.0.1.zip.txt
Sélectionnez bien les shaders que vous venez d'ajouter et faites **Apply** !

## Se connecter au serveur

Adresse IP : 51.77.137.221

## FAQ

 - **Que faire en cas de lag une fois sur le jeu ?**
	 1. Dédier plus de ressources GPU au jeu. Minecraft étant un jeu CPU-driven, la carte graphique ne travaille pas autant qu'elle le pourrait, [cette vidéo](https://www.youtube.com/watch?v=J1UcsKnIV10&ab_channel=GameTrick) permet d'y remédier !

	 2. Allouer plus de RAM à Minecraft depuis le launcher. Pour ce faire, rendez-vous dans l'onglet **Configurations** de votre launcher et modifiez le **profil Fabric**.![minecraft launcher](https://img001.prntscr.com/file/img001/StBWM162SsGp77FAmTHpGQ.jpeg)
Il vous suffira ensuite de modifier la valeur -Xmx{valeur}G selon votre configuration.
Personnellement j'ai mis 12G car j'ai 32GB de RAM, mais si vous avez par exemple 8GB, je vous conseille de mettre 4G. Pareil, si vous avez 16GB, mettez 8G.![change G value](https://img001.prntscr.com/file/img001/E00i1m7gTr-eq7G9MhqHiQ.jpeg)&nbsp;
&nbsp;

 - **Le ressourcepack et les shaders ne fonctionnent pas**
	1. Vérifiez bien que vous n'ayez pas dézippé les dossiers de ressourcepack et de shaders. Il est impératif de laisser les .zip intacts.
	2. Assurez vous que le ressourcepack et les shaders soient bien sélectionnés depuis l'interface de jeu.