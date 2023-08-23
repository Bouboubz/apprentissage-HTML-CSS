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
* Liste de police qui marche dans la plupart des naviguateurs : 
  * Arial Black
  * Futura
  * Helvetica
  * Impact
  * Trebuchet MS
  * Verdana
* Il est également possible d'utiliser une police de Google Fonts :*
  1. On copie les balises ```<link>``` que l'on colle dans les balises ```<head>``` du fichier HTML
  2. On utilise la propriété font-family dans le fichier CSS pour indiquer que l'on utilise cette police 

### Propriété sympa 

* Mettre du texte en italique avec la propriété font-style
```
em
{
    font-style: italic/normal;
}
```
* Mettre du texte en gras avec la propriété font-weight (bold = texte en gras ; normal = texte normal ; thin = texte fin)
* Souligner du texte avec la propriété texte-decoration (underline = souligné ; line-through = barré ; none = normal)
* Aligné du texte avec la propriété text-align (left = aligné à gauche ; center = texte centré ; right = aligné à droite ; justify = justifie le texte ce qui fait qu'il prend toute la largeur possible sans laisser d'espace blanc)



