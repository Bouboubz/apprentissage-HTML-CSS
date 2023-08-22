# [Chapitre 7 : Changer l'apparence du texte](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3/8061298-changez-lapparence-du-texte)

### Changer la taille du texte 

* On utilise la propriété ```font-size``` pour changer la taille du texte
* Deux type de tailles : absolue ou relative (l'un ne s'adapte pas à la plateforme du visiteur tandis que l'autre si)
* La valeur en taille absolue ce donne en pixel 
```
font-size: 16px;
```
* La valeur relative se donne de plusieurs façons différentes mais la plus fréquente est de la donner en em 
>[!NOTE]
>Une taille normale étant de 1em
>[!IMPORTANT]
>Pour un nombre décimal il faut mettre un point et non une virgule
```
<p class="elem1">Élément 1 : 1em</p>
<p class="elem2">Élément 2 : 1.3em</p>
<p class="elem3">Élément 3 : 2em</p>
```
```
.elem1 {
font-size: 1em;
}

.elem2 {
font-size: 1.3em;
}

.elem3 {
font-size: 2em;
}
```

### Choisir une police 

* On utilise la propriété ```font-family``` pour choisir la police



