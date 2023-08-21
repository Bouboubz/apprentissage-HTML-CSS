# [Chapitre 6 : Intégrer du CSS dans une page HTML](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3/8061278-integrez-le-css-dans-la-page-html)

### Lier un fichier CSS à un fichier HTML

* Pour lier un fichier CSS à un fichier HTML on utilise la balise orpheline ```<link>``` dans les balises ```<head>```
```
<head>
    <meta charset="utf-8">
    <title>Ma page</title>
    <link href="style.css" rel="stylesheet">
</head>
```
### Appliquer une propriété CSS à une balise HTML

* Trois éléments : Le sélecteur (on écrit le nom des balises que l'on veut modifier); La ou les propriétés CSS (```color ; font-size```); Leur valeur (par exemple pour ```color``` il faut indiquer la couleur)
![La base des propriété](https://user.oc-static.com/upload/2022/11/25/16693920081082_FR_1603881_HTML-CSS_Static-Graphics_p2c1-1.jpg "incroyable")
* Exemple pour changer la couleur des paragraphes : 
```
p {
    color: blue;
}
```
* Les commentaires en CSS ce font comme en C avec /* */
* Pour appliquer une même propriété à plusieurs balises ont utilise une virgule :
```
h1, p
{
    color: blue;
}
```

### Appliquer un style à un élément isolé 

* ```class``` est un élément que l'on peut accrocher sur n'importe quelle balise
```
<h1 class="voici"> </h1>
<p class="des"> </p>
<img class="classes">
```
* Dans l'attribut ```class``` on doit écrire quelque chose qui sert à identifier la balise
