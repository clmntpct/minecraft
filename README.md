# Scoobyland

Bienvenue sur **Scoobyland**, le serveur où se retrouvent tous les clebs de notre beau groupe.
Ce répo a pour but de regrouper toutes les ressources nécessaires afin d'accéder au serveur et que tout le monde soit sur un pied d'égalité en terme de textures, shaders, mods...
Suivez les étapes suivantes **dans l'ordre**, une fois celles-ci complétées, vous pourrez rejoindre le serveur sans encombre.

## 1. Installer Forge 1.19 sur son client minecraft

Forge est primordial sur le serveur car il permet d'ajouter des mods -indépendants des plugins présents sur le serveur- à son client minecraft.
Afin d'installer forge, il suffit de télécharger le [fichier source](https://github.com/Clement-picot6/minecraft/blob/main/utils/forge-1.19.2-43.1.7-installer.jar) et de cliquer dessus. Une interface s'ouvrira, il suffira de sélectionner **Install client** et valider.

![forge installer](https://img001.prntscr.com/file/img001/hptZkQs5Tm-qCvlU5aralQ.jpeg)


## Installer les mods sur son client minecraft
Deux mods sont prérequis pour lancer le serveur.
1. Optifine : c'est un mod permet d'optimiser les performances de son client minecraft. Le mod rajoute également beaucoup de réglages afin de gérer le rendu graphique de son jeu (enlever les nuages, éclaircir les ombres...). Les modifications ne sont pas globales, elles restent propre au client.
2. Simple Voice Chat : c'est un vocal de proximité (normalement tout le monde connait j'ai pas besoin d'expliquer).

Pour installer ces mods, appuyez simultanément sur **Win + R** et rentrez l'URL suivante :

    %appdata%/.minecraft/mods
Tout ce que vous avez à faire, c'est de glisser les deux fichiers du [dossiers mods du répo github](https://github.com/Clement-picot6/minecraft/tree/main/mods) dans le dossier mods de votre client minecraft.


## Sélectionner le bon profil sur son client minecraft

Après avoir installé forge, un nouveau profil a été créé sur votre client minecraft. Il est **primordial** de lancer le jeu avec ce profil, sinon **le serveur ne vous laissera pas rentrer**.

![profil forge](https://img001.prntscr.com/file/img001/UHDBCnz5Qcu-63mAy7mRWQ.jpeg)

## Ajouter le ressourcepack
Lancez votre jeu (**profil Forge**) et rendez-vous dans l'onglet **Options > Ressource Packs**. Cliquez sur **Open Pack Folder** et glissez y **Remodeled-Minecraft1.19.5.zip**.
Assurez vous ensuite de bien sélectionner le ressourcepack avant de valider. Vous devriez avoir quelque chose comme ceci :
![ressourcepack](https://img001.prntscr.com/file/img001/9a0oLoD6QMKoh6_zCvFpGg.jpeg)

## Ajouter les shaders

Même principe que pour le ressourcepack, sauf que les shaders se situent dans l'onglet **Options > Video Settings > Shaders**. Encore une fois, ouvrez le dossier des Shaders et glissez y le dossier SEUS-Renewed-v1.0.1.zip **ET** le fichier SEUS-Renewed-v1.0.1.zip.txt
Sélectionnez bien les shaders que vous venez d'ajouter !
Passons maintenant à la configuration graphique des shaders (à droite de l'écran de sélection des shaders) :
 - Si vous avez un **très** bon ordinateur : [Antialiasing: FXAA 4x] + [Render Quality: 2x] + [Shadow Quality: 2x]
 -  Si vous avez un bon ordinateur : [Antialiasing: FXAA 4x] + [Render Quality: 1.5x] + [Shadow Quality: 1.5x]
  - Si vous avez un ordinateur correct : [Antialiasing: FXAA 4x] + [Render Quality: 1x] + [Shadow Quality: 1x]

## Se connecter au serveur

Adresse IP : 51.77.137.221

## FAQ

 - **Que faire en cas de lag une fois sur le jeu ?**
	 1. Dédier plus de ressources GPU au jeu. Minecraft étant un jeu CPU-driven, la carte graphique ne travaille pas autant qu'elle le pourrait, [cette vidéo](https://www.youtube.com/watch?v=J1UcsKnIV10&ab_channel=GameTrick) permet d'y remédier !

	 2. Allouer plus de RAM à Minecraft depuis le launcher. Pour ce faire, rendez-vous dans l'onglet **Configurations** de votre launcher et modifiez le **profil Forge**.![minecraft launcher](https://img001.prntscr.com/file/img001/vtJE-utYQUKWawBp9pVz0g.jpeg)
Il vous suffira ensuite de modifier la valeur -Xmx{valeur}G selon votre configuration.
Personnellement j'ai mis 12G car j'ai 32GB de RAM, mais si vous avez par exemple 8GB, je vous conseille de mettre 4G. Pareil, si vous avez 16GB, mettez 8G.![change G value](https://img001.prntscr.com/file/img001/CUFYc4ZUTrK4y03s4WGAFg.jpeg)&nbsp;
&nbsp;

 - **Le ressourcepack et les shaders ne fonctionnent pas**
	1. Vérifiez bien que vous n'ayez pas dézippé les dossiers de ressourcepack et de shaders. Il est impératif de laisser les .zip intacts.
	2. Assurez vous que le ressourcepack et les shaders soient bien sélectionnés depuis l'interface de jeu.