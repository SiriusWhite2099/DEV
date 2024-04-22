Question :
Le code suivant est censé afficher une image, mais échoue à le faire. Pourquoi ?

Code :
```html
<img https://www.example.com/laptop.jpg />
```

Réponses :

1. La balise `<img>` ne peut afficher que des formats d'image .png ou .svg.
2. L'attribut src est manquant et doit être défini égal à l'URL de l'image, enfermé entre guillemets doubles.
3. L'URL de l'image doit être entièrement en majuscules.
4. La balise `<img>` devrait être remplacée par une balise `<image>`.

Réponse :
L'attribut src est manquant et doit être défini égal à l'URL de l'image, enfermé entre guillemets doubles.

Explication :
La balise `<img>` doit inclure un attribut src qui spécifie l'emplacement de l'image à afficher. Dans le code fourni, l'attribut src est manquant, ce qui empêche l'affichage de l'image. La syntaxe correcte pour inclure une image est `<img src="https://www.example.com/laptop.jpg" />`. Les autres réponses sont incorrectes car elles ne résolvent pas le problème de l'attribut src manquant.

