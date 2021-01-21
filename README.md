# Projet PACMAN

<div>
  <img src="https://raw.githubusercontent.com/isocpp/logos/master/cpp_logo.png" width="5%">
  <img src="https://pbs.twimg.com/profile_images/560440414667157504/ZbRVuhQ0_400x400.png" width="6%">
  <img src="https://upload.wikimedia.org/wikipedia/fr/3/32/Qt_Creator_Icon_Web.png" width="5%">
</div>

<br/>

## Team

- | <bold><a href="http://www.relave-jb.fr" target="_blank">JB Relave</a></bold> | <i>(Taz79)</i>
- | <bold>Lucie Applagnat</bold> | <i>(lucieplgnt)</i>
- | <bold>Clément Samaar</bold> | <i>(karl667)</i>
- | <bold>Lucas Charlier</bold> | <i>()</i>


## Professeurs

- | <bold>Alain Casali</bold>
- | <bold>Marc Laporte</bold>

<br/>

## Comment jouer ?
Ce PacMan est fait uniquement pour les systèmes Unix, car il utilise un système de couleurs dans le terminale qui ne fonctionnera pas sur la console de windows.
<br/>
Rendez vous sur un terminal (Linux/Mac), une fois dans le dossier PacMan executer le fichier :
<br/>
<code>
./PacMan  
</code>

<br/><br/>

# Tutoriel
## Menu
Vous pouvez naviguer entre les options avec :
- [Flèche du haut]
- [Flèche du bas]
<br/>
Vous pouvez valider votre choix avec :<br/><br/>
  [Entrée]

## Joueur
Le joueur principal est représenté par : "O"
<br/>
Il est de couleur bleue au départ.<br/>
Puis de couleur rouge quand son super pouvoir est activé.<br/>
              		
Vous pouvez le déplacer avec :
              
- [Z] Vers le haut
- [Q] Vers la droite
- [S] Vers le bas
- [D] Vers la gauche

## Monstres
Les monstres sont représentés par : "X"<br/>

Il ont chacun une couleur et deviennent bleus quand ils sont vulnérables
Si le joueur croise un monstre et qu'il n'a pas le super pouvoir il perd...
<br/>
Si le joueur mange un monstre, ce dernier réapparaîtra dans une zone de spawn au bout d'un certain temps

## Bonbons
Les bonbons sont représentés par : "*" <br/>

Si vous passez dessus, vous augmenterez votre stock de bonbons afin de finir un niveau vous devez prendre tous les bonbons
<br/>
Vous aurez votre stock de bonbons affiché en haut à gauche

## Supers Bonbons
Les supers bonbons sont représentés par : "0" <br/>
              		
Si vous passez dessus, vous activerez votre super pouvoir
Et vous pourez manger les monstres et ne pas vous faire manger pas ces derniers
    
<br/>
    
Votre super pouvoir ne dure qu'un certains temps, vous pouvez voir le temps restant en haut de l'écran.

<br/><br/>

# TRICHE !!
Si vous voulez débloquer tous les niveaux vous avez juste à remplacer le nombre dans le fichier :
<code>
Nos_fichiers/saves/level.txt  
</code>

<br/>

par "3" =)

<br/><br/>
Attention, si vous voulez modifier une map, et ne pas avoir de bug, veuillez laisser :
- "x" : La où le joueur va spawner
- "1", "2", "3", "4" : La où les 4 monstres vont spawner
- "s" : Le spawn des monstres (après mort)
