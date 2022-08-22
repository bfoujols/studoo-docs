# Changelog

### 0.6.0-alpha

**New feature :**

* New branding
* Ajout d'un fichier de lock pour vérifier les process
* Nouvelle infrastructure chez AWS

### 0.5.0-alpha

**New feature :**

* Nouveau fichier format d'import via un export Excel Academique (Plateforme Cyclables)
* Mise en place d'une commande pour installer la commande Studoo dans votre système (compatible Linux / MacOs)

### 0.4.0-alpha

**New feature :**

* Nouveau fichier format d'import via un export Excel Ecole Directe

**Fix bug :**

* Refactoring de class by Codacy

### 0.3.1-alpha

**Fix bug :**

* Problème sur la nomenclature en cas d'espace (avant / après) les noms et prénoms
* Refactoring de la classe Modèle et Dir

### 0.3.0-alpha

**New feature :**

* Test unitaire sur la simulation des commandes
* Refactoring Test FileExtension
* Finalisation du Modele par défaut

**Fix bug :**

* Correction sur le path

### 0.2.0-alpha

**New feature :**

* Commande "file:default" : Creation d'un fichier XLSX vide afin d'utiliser la commande "student:dire"
* Mise en place des tests unitaires

**Fix bug :**

* Correction pour utiliser Studoo avec la version PHP 7.4

### 0.1.0-alpha

New feature :

* Commande "student:dir" : Creation des répertoires (alias dir) de chaque étudiant dans l'arborescence
* Mise en place d'une nomenclature nom-prenom-datenaissance(aammjj) pour éviter les problèmes homonymes
* Importation des étudiants à partir d'un template au format XLSX
