[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/Cthulhus_Queen%2Fbarometre_scienceouverte_universitedelorraine/master?filepath=barometre_universite_lorraine.ipynb)


Travail inspiré du Baromètre français de la Science Ouverte : https://ministeresuprecherche.github.io/bso/ et du Baromètre Lorrain de la Science Ouverte : https://gitlab.com/Cthulhus_Queen/barometre_scienceouverte_universitedelorraine.

1) Téléchargez l'ensemble du Baromètre Inserm sur le bureau en utilisant le bouton "Download". Dé-zippez l'archive.

2) Installez la suite Anaconda Navigator (https://www.anaconda.com/products/individual).

3) Lancez Anaconda et sélectionnez Jupyter Lab. Le dossier du Baromètre Inserm téléchargé sur le bureau apparaît.

4) Faire les extractions des différentes bases de données. La liste des requêtes utilisées est dans le fichier "requetes_bdd". Remplacez les données de l'Inserm par celles de votre établissement. 

5) Dans le dossier qui est sur le bureau, enlever les fichiers inserm dans le dossier Data/raw et les remplacer par les vôtres. 
Attention, il faut reproduire très exactement le nommage des fichiers. Dans le code Inserm par exemple, le fichier 2016 du Web of Science 
s'appelle "wos_inserm_2016". Remplacez les occurrences de "inserm" par le nom de votre établissement.
Il faut également effacer le contenu du dossier 'outputs' pour enlever les éléments Inserm (mais conserver le dossier vide).

6) Ouvrir le notebook "nettoyage_donnees". Remplacer toutes les occurrences de "inserm" par le nom de l'établissement (attention : utiliser le même nom que pour les extractions de bases de données).

7) Exécutez le notebook "nettoyage_donnees" en lisant bien les instructions à chaque étape.

8) Envoyer le fichier csv généré (liste de DOI) au MESRI en suivant les instructions sur cette page : https://barometredelascienceouverte.esr.gouv.fr/a-propos/declinaisons

9) Ouvrir le notebook "barometre_inserm". Remplacer toutes les occurrences de "inserm" par le nom de l'établissement (attention : utiliser le même nom que pour les extractions de bases de données). Vous pouvez aussi renommer le notebook.

10) Exécutez le notebook "barometre_inserm" en lisant toutes les instructions. Il est possible de générer des graphiques en supprimant le '#' qui inscrit la ligne de code en commentaire. Ce choix a été fait pour afficher les graphiques mais non pour les générer car l'équipe a opté pour un affichage des visualisations avec la librairie Highcharts : https://www.highcharts.com/.

11) Les graphiques ont ensuite été codés en HTML grâce à Highcharts. Les pages réalisées pour le baromètre Inserm sont disponibles dans le répertoire 'highcharts' de ce dossier.

12) Pour ce qui est des autres visualisations, ils correspondent à la déclinaison locale du BSO national et ont été mis au point par le MESRI. Le code est disponible via le lien suivant : https://github.com/orgs/dataesr/repositories?q=bso&type=&language=&sort=

 