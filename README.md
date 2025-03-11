# Documentation 

Coucou, ceci est la documentation pour le site web de Groove et Grave.

Ce site est basé sur [Zola](https://www.getzola.org/).

pour insérer une image:
{{ image(path="/images/DSC02867_retouchée.JPG", width="60%") }}


citation:
> une quote d'un truc **important** dont vous voulez parler


Insérer une vidéo:
{{ youtube(id="8iqV9iY9gcE") }}

insérer une gallerie de photos:
{{ gallery(links=[
  "/images/DSC02507.png",
  "/images/DSC02848.png",
  "/images/DSC03069_ret.JPG",
  "/images/DSC02848.JPG",
  "/images/DSC02867_retouchée.JPG",
  "/images/DSC02252_retouchée.JPG",
  "/images/DSC02149.JPG",
  "/images/DSC02857.JPG"
]) }}
