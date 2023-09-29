# JavaScript pour le web en 24 heures

## Prérequis
Connaître HTML/CSS ou avoir suivi un cours d'initiation à l'intégration web.

## Objectif
- Apprendre JavaScript par la pratique où il sera question d'ajouter de l'interactivité, modifier le contenu ou le style d'éléments d'une page web.
- S'aider de ce support qui propose un mémo des bases essentielles pour bien appréhender ce cours
- Utiliser la doc en ligne pour une recheche plus approdondie
- Utiliser ChatGPT : Un véritable assistant, si l'on maîtrise le prompt.

## Quelques bases du langage JavaScript
- Variables et constantes
- Types de données
- Tableaux de données
- Opérations arithmétiques
- Conditions
- Boucles de répétitions

## Fonctionnalités liées au navigateur
- Référencer un ou plusieurs éléments 
- Appliquer un style css à un élément
- Ajouter / enlever une classe css à un élément
- Cliquer sur un élément 
- Lancer une fonction à intervalle de temps
- Lancer une fonction de délai

## La console 
Si vous faites un clic droit sur le navigateur, vous ouvrez un panneau inspecteur de tout ce qui est html, css et javascript.  
Pour inspecter du javascript, il faut aller dans l'onglet console.  
Cet onglet est une bénédiction quand on débute en JS, car on peut tester beaucoup de choses.

## Où placer un programme Javascript 
### 1. Dans le document html, dans une paire de balises script.
```html
<head>
    <!-- après les liens css et balise meta -->
    <script>
        // ici le programme js
    </script>
</head>
``` 

### 2. Dans un fichier externe
Un fichier porte l’extension .js.   
Le fichier peut être dans l’entête du document en en fin de page  
 ```html 
<head>
    <!-- A noter le terme defer -->
    <script src=’js/app.js’ defer></script> 
</head>
```
Pour le dire simplement : le terme defer permet au navigateur de donner la priorité au chargement de la page web.
