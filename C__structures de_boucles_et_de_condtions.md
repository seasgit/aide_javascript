# Structures de boucle
## Principe
La boucle, ou structure iterative, est un système qui permet de placer dans un bloc  
des instructions identiques que le programme doit exécuter un certain nombre de fois. 
 
## La structure for
```js 
for ( let i=0;i<=10; i++) {
    // actions
}
```
je répète des actions 10 fois en partant de 0 avec un compteur qui évolue de +1 à chaque répétition
### Exemple 1
Cet exemple, très théorique, permet de concaténer 10 fois une chaine de caractère dans une variable.  
```js
let enumeration = "";
for ( let i=0;i<=10; i++){
 enumeration += "ticket n° "+i+"-";
}
console.log(enumeration);

```
### Boucler sur un tableau
La boucle prend tout son sens avec le traitement des données dans des tableaux.  
Ci dessous, le code permet de parcourir le tableau pour mettre tous les items en majuscule.
 
```javascript
let mots = [ 'html5', 'css3', 'javascript', 'php'];
for( let i=0; i< mots.length; i++){  
      mots[i] = mots[i].toUpperCase()
}
// résultat à la sortie de la boucle
console.log(mots)
```
__A noter :__  
	L’index i commence à 0 car la position de `html5` est 0 dans le tableau.  
	La boucle s’arrête avant la longueur du tableau car le dernier élément est égal à la longueur -1.

## Boucle for of
Il existe plusieurs fonctions de boucle, celle-ci est un raccourci de la précédente.  
Ce code permet de parcourir le tableau et place chaque couleur dans une variable nommée _col_
```javascript
let colors = ['red','yellow','blue'];
for (let col of colors){
  console.log(col);
}
```
