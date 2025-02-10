Shell, I/O Redirection, and Special Characters
Description
Ce projet porte sur l'utilisation des redirections d'entrée/sortie en Shell, ainsi que la manipulation des fichiers et des flux. Vous allez créer des scripts qui interagissent avec le système de fichiers, manipulent des textes et gèrent les flux d'entrée et de sortie de manière efficace. L'accent est mis sur l'utilisation des commandes standards et des caractères spéciaux dans le Shell pour accomplir des tâches complexes.

Objectifs
À la fin de ce projet, vous serez capable de :

Expliquer ce qu'est la redirection Shell et comment elle fonctionne.
Expliquer ce que font les commandes telles que head, tail, find, wc, sort, uniq, grep, tr.
Rediriger la sortie standard vers un fichier.
Lire l'entrée standard depuis un fichier au lieu du clavier.
Enchaîner les sorties de plusieurs programmes à l'aide de redirections et de tuyaux (pipes).
Utiliser des caractères spéciaux comme les espaces, les guillemets simples et doubles, le backslash, les commentaires, les tuyaux, les séparateurs de commande, et le tilde.
Lire et comprendre les fichiers /etc/passwd et /etc/shadow.
Pré-requis
Vous devez utiliser des éditeurs comme vi, vim, ou emacs.
Vous devez créer des scripts qui seront testés sur Ubuntu 20.04 LTS.
Chaque script doit avoir exactement deux lignes de code.
Tous les fichiers doivent être exécutables.
Tâches
1. Manipulation de l'entrée et de la sortie
Les scripts doivent effectuer des redirections d'entrée/sortie dans différents scénarios :

Rediriger la sortie standard d'une commande vers un fichier.
Lire l'entrée d'un fichier au lieu du clavier.
Combiner plusieurs commandes à l'aide de redirections et de tuyaux.
2. Utilisation des commandes de filtrage
Vous allez manipuler plusieurs commandes pour filtrer les données en entrée et en sortie :

head : Afficher les premières lignes d'un fichier.
tail : Afficher les dernières lignes d'un fichier.
find : Chercher des fichiers dans un répertoire.
wc : Compter les lignes, les mots et les caractères dans un fichier.
sort : Trier les lignes d'un fichier.
uniq : Supprimer les doublons dans un fichier.
grep : Filtrer les lignes contenant un motif.
tr : Modifier des caractères dans un flux de texte.
3. Caractères spéciaux et leur utilisation
Vous devez maîtriser l'utilisation des caractères spéciaux dans le Shell :

Espaces : Séparer les arguments dans les commandes.
Guillemets simples et doubles : Pour délimiter des chaînes de caractères.
Backslash (\) : Échapper des caractères spéciaux.
Commentaires : Ajouter des commentaires dans les scripts.
Pipe (|) : Chainer plusieurs commandes.
Séparateur de commandes (;) : Exécuter plusieurs commandes dans une seule ligne.
Tilde (~) : Référencer le répertoire personnel.
4. Comprendre /etc/passwd et /etc/shadow
Vous devez être capables de lire et de comprendre les formats des fichiers système /etc/passwd et /etc/shadow :

Le fichier /etc/passwd contient des informations sur les comptes utilisateurs.
Le fichier /etc/shadow contient des informations sensibles sur les mots de passe des utilisateurs.
Exemples de Scripts
1. Afficher les 10 premières lignes d'un fichier
bash
Copier
Modifier
#!/bin/bash
head -n 10 fichier.txt
2. Afficher les 10 dernières lignes d'un fichier
bash
Copier
Modifier
#!/bin/bash
tail -n 10 fichier.txt
3. Compter le nombre de mots dans un fichier
bash
Copier
Modifier
#!/bin/bash
wc -w fichier.txt
4. Rechercher un motif dans un fichier
bash
Copier
Modifier
#!/bin/bash
grep "motif" fichier.txt
Règles Générales
Scripts à 2 lignes : Chaque script doit être exactement de 2 lignes (vous pouvez utiliser une commande sur la première ligne et une autre sur la deuxième).
Fin des scripts avec une nouvelle ligne : Assurez-vous que chaque fichier se termine par une nouvelle ligne (cela est requis par le standard).
Pas de backticks, &&, || ou ; : Ces éléments ne sont pas autorisés dans les scripts.
Pas d'utilisation de sed ou awk : Ces outils ne sont pas autorisés dans ce projet.
Tests
Les scripts seront testés sur Ubuntu 20.04 LTS, en vérifiant leur fonctionnalité par rapport aux exigences. Vous devrez utiliser les commandes de manière créative pour remplir les objectifs sans dépasser la limite de deux lignes de code.Shell, I/O Redirection, and Special Characters
Description
Ce projet porte sur l'utilisation des redirections d'entrée/sortie en Shell, ainsi que la manipulation des fichiers et des flux. Vous allez créer des scripts qui interagissent avec le système de fichiers, manipulent des textes et gèrent les flux d'entrée et de sortie de manière efficace. L'accent est mis sur l'utilisation des commandes standards et des caractères spéciaux dans le Shell pour accomplir des tâches complexes.

Objectifs
À la fin de ce projet, vous serez capable de :

Expliquer ce qu'est la redirection Shell et comment elle fonctionne.
Expliquer ce que font les commandes telles que head, tail, find, wc, sort, uniq, grep, tr.
Rediriger la sortie standard vers un fichier.
Lire l'entrée standard depuis un fichier au lieu du clavier.
Enchaîner les sorties de plusieurs programmes à l'aide de redirections et de tuyaux (pipes).
Utiliser des caractères spéciaux comme les espaces, les guillemets simples et doubles, le backslash, les commentaires, les tuyaux, les séparateurs de commande, et le tilde.
Lire et comprendre les fichiers /etc/passwd et /etc/shadow.
Pré-requis
Vous devez utiliser des éditeurs comme vi, vim, ou emacs.
Vous devez créer des scripts qui seront testés sur Ubuntu 20.04 LTS.
Chaque script doit avoir exactement deux lignes de code.
Tous les fichiers doivent être exécutables.
Tâches
1. Manipulation de l'entrée et de la sortie
Les scripts doivent effectuer des redirections d'entrée/sortie dans différents scénarios :

Rediriger la sortie standard d'une commande vers un fichier.
Lire l'entrée d'un fichier au lieu du clavier.
Combiner plusieurs commandes à l'aide de redirections et de tuyaux.
2. Utilisation des commandes de filtrage
Vous allez manipuler plusieurs commandes pour filtrer les données en entrée et en sortie :

head : Afficher les premières lignes d'un fichier.
tail : Afficher les dernières lignes d'un fichier.
find : Chercher des fichiers dans un répertoire.
wc : Compter les lignes, les mots et les caractères dans un fichier.
sort : Trier les lignes d'un fichier.
uniq : Supprimer les doublons dans un fichier.
grep : Filtrer les lignes contenant un motif.
tr : Modifier des caractères dans un flux de texte.
3. Caractères spéciaux et leur utilisation
Vous devez maîtriser l'utilisation des caractères spéciaux dans le Shell :

Espaces : Séparer les arguments dans les commandes.
Guillemets simples et doubles : Pour délimiter des chaînes de caractères.
Backslash (\) : Échapper des caractères spéciaux.
Commentaires : Ajouter des commentaires dans les scripts.
Pipe (|) : Chainer plusieurs commandes.
Séparateur de commandes (;) : Exécuter plusieurs commandes dans une seule ligne.
Tilde (~) : Référencer le répertoire personnel.
4. Comprendre /etc/passwd et /etc/shadow
Vous devez être capables de lire et de comprendre les formats des fichiers système /etc/passwd et /etc/shadow :

Le fichier /etc/passwd contient des informations sur les comptes utilisateurs.
Le fichier /etc/shadow contient des informations sensibles sur les mots de passe des utilisateurs.
Exemples de Scripts
1. Afficher les 10 premières lignes d'un fichier
bash
Copier
Modifier
#!/bin/bash
head -n 10 fichier.txt
2. Afficher les 10 dernières lignes d'un fichier
bash
Copier
Modifier
#!/bin/bash
tail -n 10 fichier.txt
3. Compter le nombre de mots dans un fichier
bash
Copier
Modifier
#!/bin/bash
wc -w fichier.txt
4. Rechercher un motif dans un fichier
bash
Copier
Modifier
#!/bin/bash
grep "motif" fichier.txt
Règles Générales
Scripts à 2 lignes : Chaque script doit être exactement de 2 lignes (vous pouvez utiliser une commande sur la première ligne et une autre sur la deuxième).
Fin des scripts avec une nouvelle ligne : Assurez-vous que chaque fichier se termine par une nouvelle ligne (cela est requis par le standard).
Pas de backticks, &&, || ou ; : Ces éléments ne sont pas autorisés dans les scripts.
Pas d'utilisation de sed ou awk : Ces outils ne sont pas autorisés dans ce projet.
Tests
Les scripts seront testés sur Ubuntu 20.04 LTS, en vérifiant leur fonctionnalité par rapport aux exigences. Vous devrez utiliser les commandes de manière créative pour remplir les objectifs sans dépasser la limite de deux lignes de code.
