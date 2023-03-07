# BattleShip AI

## Sommaire :
1. Présentation du projet
2. Language et librairies utilisés
3. Lancement du programme
4. Captures d'écran

## I) Présentation du projet
Tusmo reprend le concept du célébre jeu Motus mais directement sur naviguateur. L'utilisateur se verra affecter un mot contenant un certain nombre de lettres qu'il devra trouver dans la limite des 6 essais. Un essai n'est validé que si le mot existe dans le dictionnaire francais. Pour l'aider, le jeu lui indiquera en orange les lettres présentes dans le mot mais mal placé et en rouge les lettres situés à la bonne place. A la fin de la partie l'utilisateur aura la possibilité de copier le résultat de sa partie dans le presse-papier pour le comparer avec d'autre joueurs et il aura également accès à un panneau regroupant ses statistiques.


## II) Language et outils utilisés
Le projet est bien sur majoritairement en JS avec la bibliotéque React. La liste de mots possible est un simple fichier JSON d'où l'on tirera aléatoirement un mot et la vérification de la validité des mots se fait également grâce à ce fichier.

## III) Lancement du programme

Après avoir cloné le projet et à la racine :
```
npm i
``` 
Puis toujours à la racine :

```
npm start
```
Et voilà aussi simplement que ca, le projet devrait se lancer dans une fenêtre de votre naviguateur, si ce n'est pas le cas, il suffit d'aller à l'adresse indiquée dans le terminal.


## IV) Captures d'écran
<div style="text-align: center">
    
### Menu du site

    
<br>
<p><img src="https://i.imgur.com/mh5iNur.png" /></p>
<br>

---
### Début de partie

<br>
<p><img src="https://i.imgur.com/ka69y88.png" /></p>
<br>
<p><i>Un indice est donné à chaque partie sous la forme de la première lettre du mot</i></p>
<br>

---
### Partie en cours

<br>
<p><img src="https://i.imgur.com/iaS3l8k.png" /></p>
<br>
<p><i>Les différentes lettres en orange et rouge permettent de trouver que le mot est "envoyer"</i></p>
<br>

---
### Partie gagné
<br>
<p><img src="https://i.imgur.com/jkAgPb8.png" /></p>
    <i>Exemple de récapitulatif de partie</i><br>
🟥⚫🟠⚫⚫🟥🟥<br>
🟥🟥🟠🟥⚫⚫⚫<br>
🟥🟥🟥⚫🟠🟠⚫<br>
🟥🟥🟥🟥🟥🟥🟥
<br>
    
---
### Partie perdue

<br>
<p><img src="https://i.imgur.com/Z0nmsYN.png" /></p>
<br>
<br>
    
---
### Exemple de mot non valide

<br>
<p><img src="https://i.imgur.com/Rl7l2QG.png" /></p>
<br>
<br>
    
---
### Ecran de statistiques

<br>
<p><img src="https://i.imgur.com/0aXKKfC.png" /></p>
<br>
<br>
</div>
