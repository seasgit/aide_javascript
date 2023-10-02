# Introduction
Un programme peut manipuler des données de type nombre, chaines de caractères, tableaux ou listes, voire plus complexes. 
A notre niveau, nous nous limiterons à deux ou trois types :  nombres, chaines de caractères et tableaux.


# En préambule 
## des commentaires
Avant de faire des tests sur les différents types de données, il est bon de savoir créer des commentaires dans un script
```js
    // commmentaire sur une ligne

    /*
        bloc de commentaire
        sur plusieurs
        lignes.
    */
```
## méthodes de tests
Les types de données présentés ci-dessous peuvent être testés 
- depuis le script avec la fonction `console.log()`
- directement en tapant tout dans la console

# Nombres
- nombres entiers et decimaux
```js
    let nombre = 100
    // A noter ci dessous le point, et non la virgule.
    let prix = 35.45
    // test de la 1ère variable dans la console du navigateur
    console.log(nombre)

```
## Quelques opérations 
###  Incrémenter les nombres
C'est l'action de modifier la valeur d'une variable en ajoutant 1 ou plus
```js
let score = 12
// ici on ajoute 1
score ++ 
// ici on ajoute 4
score +=4
// test dans la console du navigateur
console.log(score)
```
### Décrémenter les nombres
C'est la même syntaxe avec le signe moins.

### Multiplier, diviser les nombres
```js
let prix = 120
// divisé par 2
prix /= 2
// multiplié par 2
prix *=2
```
# Chaines de caractères (string)
## Les délimiteurs 
Les chaines de caractères sont délimitées par des quotes ou des guillemets.  
Ci dessous quelques exemples avec les deux délimiteurs
```js
    let texte1 = 'Ce chat est magnifique'
    // ou
    let texte1 = "Ce chat est magnifique"
    // Ici, on a une citation, les délimiteurs sotn les simples quotes
    let texte =  'Et là on dit : "Merci qui ?"'
```
## concaténer des chaînes de caractères.
Traductions : mettre bout à bout  - coller - fusionner.

# Les tableaux simples 
Le tableau permet de regrouper des données qui sont en général de même type.   
C'est un premier pas vers les bases de données, car on peut faire les actions suivantes : 
- insérer 
- effacer
- lire un élément selon une position donnée.
- pour ne citer que cela ... 
###  Attention : On compte les éléments d'un tableau  à partir de 0

## Tests depuis la console
```js
// déclarer un tableau avec trois couleurs
let tab_couleurs = ['rouge', 'vert', 'bleu', 'jaune']
// lire la troisième valeur
tab_couleurs[2]  
// OU, déclarer un tableau vide
let tab_couleurs = [];
// insérer au début
tab_couleurs.unshift('rouge')

```
## Tests depuis le fichier script avec une sortie console
```js
// déclarer un tableau avec trois couleurs
let tab_couleurs1 = ['rouge', 'vert', 'bleu', 'jaune']
// lire la troisième valeur
console.log(tab_couleurs1[2])
// OU déclarer un tableau vide
let tab_couleurs = [];
// insérer au début
tab_couleurs.unshift('rouge')

```

# Un objet
Pour simplifier au mieux, disons qu'un objet est une donnée dotée de propriétés.  
Cela s'avère très pratique pour structurer l'information.
```javascript
// objet et ses propriétés
let employe = {  
  nom : "Louis", 
  metier : "Webdesigner", 
  ville : "Paris"  
};

// lire une propriété
let residence_employe =  employe.ville;
console.log(residence_employe);
```

# Les tableaux d'objets
Un développeur a besoin très rapidement de connaître ou recourir à ce genre de tableau plus complexe. 

```javascript
let employees = [
  {  nom : "Louis", metier : "Webdesigner", ville : "Paris"  },
  {  nom : "Luca", metier : "Développeur", ville : "Lyon"  },
  {  nom : "Jean", metier : "Directeur", ville : "Lille"  }
];

let e1 =  employees[0];
console.log(e1.nom);

// raccourci
console.log(employees[0].nom);
```




