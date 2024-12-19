# Configuration DNS

Ce repository contient les fichiers de configuration DNS pour les domaines de l'ALBM.

## Configuration

Les fichiers de configuration sont au format BIND9 et sont situés dans le répertoire `zones`.
Le fichier `common` contient les configurations communes à tous les domaines, il faut l'inclure dans chaque fichier de zone.

### albm.fr.

Le fichier `albm.fr.` contient la configuration du domaine `albm.fr.`.
Il inclut le fichier `common` et définit les enregistrements spécifiques à ce domaine.