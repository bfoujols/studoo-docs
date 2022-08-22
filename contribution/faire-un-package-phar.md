# Faire un package (phar)

Le package du projet se fait via une archive ".phar" avec la librairie "clue/phar-composer"

{% hint style="danger" %}
Il est nécessaire d'effectuer les tests avant de packager
{% endhint %}

### Effectuer les tests

```bash
composer test
```

Cette commande est raccourcie via l'outil Composer. Il exécute la commande suivante :&#x20;

```bash
php vendor/bin/phpunit --testdox tests
```

Plus d'information sur la page "Testing" :

{% content-ref url="testing.md" %}
[testing.md](testing.md)
{% endcontent-ref %}

### Création du package

1/ La création du package nécessite une librairie "clue/phar-composer"

```bash
curl -JOL https://clue.engineering/phar-composer-latest.phar
```

2/ Téléchargement des sources

```
git clone git@github.com:bfoujols/studoo.git
```

3/ Entrer dans le répertoire des sources

```bash
cd studoo
```

4/ Télécharger les vendors (librairie) via composer

```bash
composer install --no-dev
```

5/ Revenir au répertoire racine pour exécution du package

```batch
cd ..
```

6/ Excécuter la commande pour création de l'exécutable

```bash
php -d phar.readonly=off phar-composer.phar build studoo
```

_Résultat :_&#x20;

```
[1/1] Creating phar mstud.phar
  - Adding main package "bfoujols/studoo"
  - Adding composer base files
  [...]
  - Setting main/studoo
    Using referenced shebang "#!/usr/bin/env php"
    Using referenced chmod 0644
    Applying chmod 0644
    OK - Creating studoo.phar (1091.6 KiB) completed after 0.1s
```

_7/ Vérification du bon fonctionnement de l'exécutable_

```bash
php studoo.phar --version
```
