# [Chapitre 4 : Créer un lien hypertexte en HTML](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3/1604646-creez-un-lien-hypertexte-en-html)

### Les liens hypertexte

* Un lien hypertexte (ou hyperlien) permet de changer de page. Par défaut, il est en bleu et souligné dans le navigateur mais on peut modifier ce style en CSS.
* Pour faire un lien hypertexte vers un site web existant, on utilise la balise ```<a>``` avec l'attribut  href pour indiquer l'adresse de la page web cible. Il s'agit d'un lien absolu. Exemple :  ```<a href="https://openclassrooms.com">```
* Pour faire un lien hypertexte vers une autre page de son site, on utilise la balise ```<a>```  avec l'attribut  href pour indiquer le nom du fichier en local. Il s'agit d'un lien relatif. Exemple :  ```<a href="page2.html">```
* Si les deux pages sont situé dans deux dossiers différents en local on indique le chemin jusqu'au contenu : ```<a href="contenu/autredossier/page3.html">Page 3</a>``` ; Si le fichier cible est situé dans un fichier plus haut on utilise deux points : ```<a href="../page3.html">Page 3</a>```
* Un lien hypertexte peut aussi permettre d'amener vers un endroit précis d'une page. Il faut créer une ancre avec l'attribut  id  pour “marquer” cet endroit dans la page, puis faire un lien vers l'ancre comme ceci :  ```<a href="#ancre">```
```
<h1>Ma grande page</h1>
<p>
Découvrez nos conseils d’aménagement pour :<br>
    <a href="#cuisine">La cuisine</a><br>
    <a href="#jardin">Le jardin</a><br>
    <a href="#salon">Le salon</a><br>
</p>
<h2 id="cuisine">La cuisine</h2>
<p>... (beaucoup de texte) ...</p>
<h2 id="jardin">Le jardin</h2>
<p>... (beaucoup de texte) ...</p>
<h2 id="salon">Le salon</h2>
<p>... (beaucoup de texte) ...</p>
```
* Si l'ancre est situé sur une autre page il faut le mettre avant le #
```
<h1>Le Mégamix</h1>
<p>
Rendez-vous quelque part sur la page :<br>
    <a href="index.html#cuisine">La cuisine</a><br>
    <a href="index.html#jardin">Le jardin</a><br>
    <a href="index.html#salon">Le salon</a><br>
</p>
```
* Comportement particulier : ```target="_blank"``` = lien qui s'ouvre dans un nouvel onglet
                             ```href="mailto:NOMDUMAIL@MAIL.COM"``` = lien qui ouvre boite mail avec adresse et mail vide
                             ```href="NOMDEFICHIER.EXTENSION"``` = permet de télécharger le fichier qui est dans le même dossier