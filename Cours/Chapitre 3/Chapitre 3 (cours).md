# Chapitre 3 : Organiser son texte 

### Les balises

* Créer des paragraphes avec les balises <p> </p>
```
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8">
        <title>Ma page</title>
    </head>
    <body>
        <p>Ceci est le contenu de mon premier paragraphe</p>
        <p>Ceci est le contenu de mon deuxième paragraphe</p>
    </body>
</html>
```
* Balise orpheline pour revenir à la ligne : ```<br>``` (attention à ne pas trop en enchainer)
```
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8">
        <title>Ma page</title>
    </head>
    <body>
        <p>Ceci est le contenu de mon premier paragraphe, <br>dont le contenu est particulièrement long.</p>
        <p>Ceci est le contenu de mon deuxième paragraphe</p>
    </body>
</html>
```
* Les titres avec les balises allant de ```<h1>``` à ```<h6>``` (structurer en fonction de l'importance des titres)
```
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="UTF-8">
        <title>Ma page</title>
    </head>
    <body>
        <h1>Bienvenue sur ma page</h1>
        <p>Ceci est le contenu de mon premier paragraphe</p>
        <p>Ceci est le contenu de mon deuxième paragraphe</p>
        <h2>Voilà mon sous-titre 1</h2>
        <h3>Une sous-partie</h3>
        <p>Un paragraphe</p>
        <h3>Une autre sous-partie</h3>
        <p>Tiens encore un paragraphe</p>
        <h2>Voilà mon sous-titre 2</h2>
        …
    </body>
</html>
```
* Les balises pour écrire des listes : ```<li> et <ul> ou <ol>```
  On balise les éléments d'une liste avec ```<li>``` pour indiquer que c'est une liste puis on indique si elle est ordonée avec ```<ol>``` ou si elle ne l'est pas ```<ul>```
```
  <h1>Les fruits rouges</h1>
<ul>
   <li>Fraises</li>
   <li>Framboises</li>
   <li>Groseilles</li>
</ul>

<h1>Ma journée</h1>
<ol>
   <li>Je me lève.</li>
   <li>Je mange et je bois de l'eau.</li>
   <li>Je retourne me coucher.</li>
</ol>
```
* Mettre en valeur du texte :
| Balises | Traduction par le naviguateur |
|--- |--- |
| <mark></mark> | Surligner le texte |
| <em></em> | Mettre le texte en italique |
| <strong></strong> | Mettre le texte en gras |