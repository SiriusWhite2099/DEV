Question :
Pourquoi le code ci-dessous est-il incorrect ?

Code :
```
<video src="myVid.mp4" controls >
```

Réponses :

1. Une balise auto-fermante valide se termine par />.
2. La largeur et la hauteur de la vidéo doivent être spécifiées.
3. La source de la vidéo myVid.mp4 (src=) n'est pas valide.
4. L'élément vidéo n'est pas une balise auto-fermante. Il devrait avoir une balise d'ouverture et une balise de fermeture.

Réponse :
Le code est incorrect parce que :
```
4. L'élément vidéo n'est pas une balise auto-fermante. Il devrait avoir une balise d'ouverture et une balise de fermeture.
```

Explication :
La balise `<video>` est un élément HTML qui permet d'inclure des vidéos dans une page web. Contrairement à certaines autres balises comme `<img>` qui sont auto-fermantes, la balise `<video>` nécessite une balise d'ouverture `<video>` et une balise de fermeture `</video>`. Dans le code donné, il manque la balise de fermeture `</video>`, ce qui le rend incorrect.