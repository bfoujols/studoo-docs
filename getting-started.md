# Getting started

### Prérequis

| Service      | Version |
| ------------ | ------- |
| MAC OS       | ^10.11  |
| LINUX Kernel | ^4.11   |
| PHP Engine   | ^7.4    |
| PHP Ext CLI  | ^7.4    |
| CURL         | ^7.6    |

### Installation

Il y a 2 manières d'installer la commande :&#x20;

#### Via installer

Pour installer la commande, ouvrez un terminal :

```bash
curl -fsS https://raw.githubusercontent.com/bfoujols/studoo/main/dist/installer.php | php
```

_Résultat_

```shell
Studoo installerStudoo installer
  [*] Success to download Manifest 

Environment check
  [*] The "json" PHP extension est installé.
  [*] The "phar" PHP extension est installé.
  [*] The "openssl" PHP extension est installé.
  [*] The "pcre" PHP extension est installé.
  [*] La version de PHP est OK (***)

Téléchargement
  [*] Le téléchargement est réussi
  [*] Le check d'intégrité est OK
  [*] Le Phar est valide

Installation
  [*] Le Phar est executable
  [*] La création du dossier OK /***/***/.studoo/bin
  [*] Déplacement Phar OK: /Users/redbull/.studoo/bin/studoo

Action à faire
  Mettre dans votre fichier configuration shell, la ligne suivante :  export PATH=$HOME/.studoo/bin:$PATH
  Après l'installation de cette ligne, vous pouvez ouvrir une autre session de terminal
  La commande studoo est disponible :)
  Si vous avez un problème, https://github.com/bfoujols/studoo/discussionss
```

Vous pouvez utiliser la commande :

```shell
php ~/.studoo/bin/studoo list
```

{% hint style="info" %}
Nous vous conseillons de rendre globale la commande en l'ajoutant dans le fichier de configuration de votre shell
{% endhint %}

#### Via le téléchargement de l'archive

Néanmoins si vous ne voulez pas l'installer, vous pouvez utiliser la commande en téléchargeant l'exécutable.

[https://github.com/bfoujols/studoo/tags](https://github.com/bfoujols/studoo/tags)

Vous pouvez exécuter studoo&#x20;

```
php studoo.phar list
```

{% hint style="warning" %}
N'oubliez pas de rendre les bons droits d'exécution pour lancer la commande
{% endhint %}



\
