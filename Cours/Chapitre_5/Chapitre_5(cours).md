# [Chapitre 5 : Insérer des images](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3/8061269-inserez-des-images)

### Insérez une image 

* Il existe plusieurs formats d'images adaptés au Web : PNG, JPG…
* On insère une image avec la balise ```<img>```
* On  utilise deux attributs en particulier : ```src``` qui permet d'indiquer la source de l'image et ```alt``` qui donne une description alternative à l'image (qui sera écrite si l'image à du mal à s'afficher ou qui sera lu si naviguateur en mode handicap)
```
<p>
Voici une très belle photo que j'ai trouvée sur Unsplash :<br>
<img src="images/paysage.jpg" alt="Photo de plage vue du dessus" />
</p>
```
* Ajouter une infobulle avec l'attribut ```title``` qui afficher un texte quand on survole l'image
* Utile de faire des miniatures cliquables si image trop grande. Afficher une image réduite qui quand on clique dessus renvoir vers l'image plus grande. 
```
<p>Vous souhaitez voir l'image dans sa taille d'origine ? Cliquez dessus !<br>
    <a href="images/montagne.jpg"><img src="images/montagne_mini.jpg" alt="Chemin de randonnée au milieu des montagnes" title="Cliquez pour agrandir" ></a>
</p>
```