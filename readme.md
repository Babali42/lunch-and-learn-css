# Talk : Point besoin de classe pour bien sélectionner

John et Baptiste - 25/03/2024

*Reprendre le code supprimer tout les styles sauf le layer, et suivre les étapes suivantes pour apprendre ou réviser les
sélecteurs css*

# Etapes

- labels pas sélectables
- divs dans li pas sélectables (elem)
- textes dans li en italique (desc)
- textes dans li pas en italique au premier niveau (child)
- texte "Connaissez-vous les sélecteurs css ?" en gras (+)
- input du mail avec un fond jaune clair
- texte "Connaissez-vous les sélecteurs css ?" en gras (:checked) seulement si la case est cochée
- mail avec une bordure rouge si invalid et style différent au focus (:invalid et :focus)
- fieldset en display:none quand la case est cochée (~ :not)
- imbriquer la règle fieldset dans la règle :not(:checked)
- libellé du email rouge quand le contenu est invalide (#, :has)
- input invalides avec un background rouge (:invalid)
    - usage du :where pour enlever la spécificité du sélecteur contenu dans le where
- mettre une bordure rouge au fieldset s'il contient un input qui n'est pas checked
- ne pas mettre la bordure en rouge si le input n'est pas de type checkbox ([])

# Layer

mention du !important dans un layer

# Conclusion

On peut utiliser des classes pour sélectionner des éléments mais ce n’est pas l’unique moyen de faire et que dans
certains cas (petits composants avec des styles isolés) il peut être intéressant d’utiliser d’autres sélecteurs

## Titre alternatif

Point besoin de classe(s) pour le css!

# Slides
![Slide1.jpg](images%2FSlide1.jpg)
![Slide2.jpg](images%2FSlide2.jpg)
![Slide3.jpg](images%2FSlide3.jpg)
![Slide4.jpg](images%2FSlide4.jpg)
![Slide5.jpg](images%2FSlide5.jpg)
![Slide6.jpg](images%2FSlide6.jpg)
![Slide7.jpg](images%2FSlide7.jpg)
![Slide8.jpg](images%2FSlide8.jpg)
![Slide9.jpg](images%2FSlide9.jpg)
![Slide10.jpg](images%2FSlide10.jpg)