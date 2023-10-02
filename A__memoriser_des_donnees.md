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


# Mémoriser des données 
un programme Javascript a besoin de garder en mémoire les données textuelles, numériques qu'il traite.  

# Variables 
Comme son nom l'indique, une variable peut mémoriser une information qui peut évoluer au fil de l'exécution du programme.
## Syntaxe
```js
    // affectation de la valeur 10 à la variable nombre
    let un_nombre = 10
    // lire la variable dans la console du navigateur
    console.log(un_nombre)
    // modification
    nombre = 15
    // ou opération pour ajouter la valeur 5
    nombre +=5
    console.log(un_nombre)

```
# Constantes
Comme son nom l'indique, une constante peut mémoriser une information et empêcher tout modification
## Syntaxe
```js
    // la constante garde en mémoire 31
    const HG = 31
    // toute modification échoue
    HG = 34
    // Exp de message en retour :  TypeError: Assignment to constant variable

```
