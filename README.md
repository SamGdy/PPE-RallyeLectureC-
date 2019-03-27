# PPE-RallyeLectureC#

Interface de création des identifiants des élèves du site Rallye lecture à partir d'un fichier CSV.

Le projet est divisé en 3 grandes parties :

* Lecture des informations d'un fichier csv.
* Ecriture d'un fichier csv avec les informations de connection de chaques eleves.
* Alimentation d'une base de données.

Les outils mis en oeuvre : 

* Visual Studio
* C#
* Windows Form
* Git

Tout d'abord nous avons créée la base de données pour acceuillir et traiter ces informations :

![Capture.png](https://github.com/SamGdy/PPE-RallyeLectureC-/blob/master/BddRallyeLecture.PNG)

Le logiciel se présente ainsi : L'enseignant s'identifit aux logiciel.

![Capture.png](https://github.com/SamGdy/PPE-RallyeLectureCSharp/blob/master/Identification.PNG)

Après s'être identifié, il à accès au logiciel 

Il peut choisir un ou plusieur fichier CSV ou se trouve le nom de famille et le prénom des élèves.

![Capture.png](https://github.com/SamGdy/PPE-RallyeLectureCSharp/blob/master/logiciel.PNG)

Une fois le fichier sélectionné, l'enseignant va définir la classe, le niveau, et si le mot de passe doit être généré aléatoirement ou pas.

Fichier original / Fichier créée

![Capture.png](https://github.com/SamGdy/PPE-RallyeLectureCSharp/blob/master/CsvEleve.PNG)     ![Capture.png](https://github.com/SamGdy/PPE-RallyeLectureCSharp/blob/master/CsvEleveIdentification.PNG)


