# Traduction pour le jeux Academia School Simulator en Français.
A l'origine fait par haru_dr

Modification fait par moi-même SteamId: Brice Willus.

Le fichier de modification se trouve dans le répertoire **Language**.
**Academia_French.xml** est le fichier de traduction

## Annotations
Pour modifier un commentaire de traduction:

Remplacer
``` 
<translatorComment />
```

par
```
<translatorComment></translatorComment>
```

Il est conseiller de mettre des attributs quand on fait un changement par exemple pour savoir qui fait un changement. Par exemple :

```
<translatorComment isModifiyBy="BW"></translatorComment>
```

au lieu de mettre des \*new\* un peu partout. ^^'

## Comment faire la traduction

C'est simple il faut juste mettre le texte entre les balises \<translation\> :

```
<translation> ## Ici le texte à traduire ## </translation>
```

**ATTENTION** Ne pas supprimer les chiffres entre accolades le jeu y met ses variables. exemple à la *ligne 1852* :

```
    <term id="GrantUnlockedNotification" isDone="false" isChanged="false">
      <devComment />
      <translatorComment />
      <translation>Vous avez ouvert {0} Subvention!</translation>
    </term>
```

**NE PAS METTRE D'ESPACE ENTRE LES ACCOLLADES** 

Vous pouvez mettre par contre un espaces avant et après les accolades. Mais pas à l'intérieur.

## Changelog

**0.0.5** : Fin de la première vagues de correction avec des points dans les descriptions et les espaces avant les points d'exclamation et d'intérrogation.

**0.0.4** : Correction des espaces avant les signes de ponctuations comme les point d'exclamations. Arrêt des coorection à la *ligne 2061*

**0.0.3** : Changement du fichier previewImages.png, mise à jour du fichier ModData.json.  

**0.0.2** : Suppression des annotations dans les commentaires \*new\* et création du fichier README.md

**0.0.1** : Mise à jour des accents. 