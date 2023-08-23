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

### Appliquer un style à un élément isolé avec l'attribut ```class```

* ```class``` est un élément que l'on peut accrocher sur n'importe quelle balise
```
<h1 class="voici"> </h1>
<p class="des"> </p>
<img class="classes">
```
* Dans l'attribut ```class``` on doit écrire quelque chose qui sert à identifier la balise
```
<body>
    <h1>Titre principal</h1>
    <p>Ceci est le contenu de mon premier paragraphe</p>
    <p class="bleu">Ceci st le contenu de mon deuxième paragraphe</p>
    <h2>Voilà mon sous-titre h2</h2>
</body>
```
* Puis dans notre fichier CSS on indique le nom de la classe précédé d'un point 
```
.ma-classe {
    color: #663399;
}
```
### Appliquer un style à un élément isolé avec l'attribut ```id```
 
* Fonctionne de la même facon que ```class``` mais peut être utilisé qu'une seule fois dans le code
* Pas utile en HTML mais en JS
* Marquer et appeler un élément (on utilise un # au lieu d'un point)
```
<img src="images/logo.png" alt="Logo du site" id="logo">
```
```
#logo {
/* Indiquez les propriétés CSS ici */
}
```
### Appliquer plusieurs propriétés CSS d'un coup à un élément

* Il est possible de cumuler les styles en cumulant plusieurs ```class``` sur une même balise
```
<body>
    <h1>Titre principal</h1>
    <p>Ceci est le contenu de mon premier paragraphe</p>
    <p class="ma-classe grand-texte">Ceci est le contenu de mon deuxième paragraphe</p>
    <h2 class="grand-texte">Voilà mon sous-titre h2</h2>
</body>
``` 
* Il est également possible d'ajouter plusieurs propriétés sur un même sélecteur 
```
balise1
{
    propriete1: valeur1;
    propriete2: valeur2;
/* … */
}
```

### Exploitation des balises universelles

* Si l'on souhaite modifier le style d'un ou plusieurs mots dans une phrase et qui ne sont pas entourés par des balises on utilise des balises universelles
* Une balise universelle = balise avec aucune signification particulière 
* ```<span></span>``` et ```<div></div>```
* La balise span est une balise de type "inline" (une balise que l'on place au seins d'un paragraphe)
* La balise div est une balise de type "block" qui entoure un bloc de texte (comme ```<p>``` ou ```<h1>```) utilisé souvent dans mise en page

