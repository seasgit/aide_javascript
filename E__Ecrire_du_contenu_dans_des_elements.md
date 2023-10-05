
# Ecrire du contenu textuel
## contenu texte brut 
Nous voulons écrire un texte à l'intérieur du h1 grâce à javaScript.  
```js
const titreSection = document.querySelector('section h1')
// on utilise une propriété textContent
titreSection.textContent =  "Hello World!";
// tester avec la console
console.log( titreSection)
```
## contenu html
Ici on va pouvoir ajouter du contenu plus riche, avec l'intégration de balises et de style par exemple.
```js
// on utilise une propriété innerHTML
titreSection.innerHTML =  "Les langages du <span style='color:red'>WEB</span>"
// tester avec la console
console.log( titreSection)
```
   


