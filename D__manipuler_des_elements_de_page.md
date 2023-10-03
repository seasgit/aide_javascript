# Sélectionner un élément de page
## querySelector
```js
// Dans le document je sélectionne le titre d'une section
document.querySelector('section h1');
// tester avec la console
console.log( document.querySelector('section h1'))

```
# Ecrire du contenu textuel
## contenu texte brut 
Nous voulons écrire un texte à l'intérieur du h1 grâce à javaScript.  
```js
// on utilise une propriété textContent
document.querySelector('section h1').textContent =  "Hello World!";
// tester avec la console
console.log( document.querySelector('section h1'))
```
## contenu html
Ici on va pouvoir ajouter du contenu plus riche
```js
// on utilise une propriété textContent
document.querySelector('section h1').innerHTML =  "Les langages du <strong>WEB</strong>"
// tester avec la console
console.log( document.querySelector('section h1'))
```

## Utilisation d'un constante
On peut raccourcir l'instruction pour plus de lisibilité
```js
const titreSection = document.querySelector('section h1')
titreSection.textContent =  "Hello World!";
// OU
titreSection.innerHTML =  "Les langages du <strong>WEB</strong>"
// tester avec la console
console.log( titreSection)
```

   


