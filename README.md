# Welcome

Création d'un invité de commande pour faciliter la gestion des étudiants.&#x20;

L'objectif est simple : Éviter des tâches récurrentes et fastidieuses

À partir de fichier source (XLS, CVS, JSON ...), on agrège des données pour effectuer des tâches. Voici des exemples :&#x20;

* Création des dossiers d'étudiant
* Élaboration d'une arborescence
* Création des fiches d'examen
* Création de compte&#x20;

### Liste des features

* :tada: NEW : Importation des étudiants à partir d'un export Cyclables (Adacemie)
* Importation des étudiants à partir d'un export Ecole Directe
* Commande "student:dir" : Creation des répertoires (alias dir) de chaque étudiant dans l'arborescence
* Commande "file:default" : Creation d'un fichier XLSX vide afin d'utiliser la commande "student:dir"
* Mise en place d'une nomenclature nom-prenom-datenaissance(aaaammjj) pour éviter les problemes homonyme
* Importation des étudiants à partir d'un template au format XLSX (file:default)

Plus d'information sur la liste des livraisons :

{% content-ref url="changelog.md" %}
[changelog.md](changelog.md)
{% endcontent-ref %}

