# Mémento Projet TP commande Terminal 

## Étape 1 : Se repérer

- Pour afficher le chemin du dossier mettez la commande "pwd"

- Pour afficher son contenu la commande est "ls"

- Pour voir les fichiers cachés la commande est "ls -a"

- Pour voir les fichiers en version longue avec les fichiers cachés la commande est "ls -la"

- Pour afficher l'aide à la commande ls la commande est "ls --help"

- Pour se déplacer dans le dossier Documents la commande est "cd Documents"

- Puis pour voir ce qu'il y a à l'intérieur la commande est "ls"

## Étape 2 : Organiser un projet 

- Pour créer le dossier station-meteo il faut utiliser la commande "mkdir station-meteo" ensuite entrer dedans avec la commande " cd station-meteo/"

- Après ça créer dans le dossier station-meteo un dossier brouillon avec le sous-dossier data avec cette commande "mkdir -p brouillon/data"

- Ensuite créer les 3 fichiers : src, test et docs en une seule commande à la racine de station-meteo avec la commande "mkdir src test docs"

- Après ça entrer dans le dossier brouillon avec la commande "cd brouillon/" après ça créer un fichier qui se nommera main.py où sera inscrit "print("Station météo prête")" avec la commande " echo "print("Station météo prête")" > main.py" ou en une fois "echo 'print("Station météo prête")' > brouillon/main.py"

- Pour déplacer le fichier main.py et le dossier data à la racine "mv data/ main.py ../ " ensuite pour déplacer le fichier main.py au dossier src la commande est " mv main.py src"

- Pour supprimer le dossier brouillon la commande est "rm -r brouillon"

*Pour exécuter le code python on doit d'abord entrer dans le dossier src avec la commande "cd src/" ensuite lancer le fichier main.py avec la commande "py main.py"*

## Étape 3 : Manipuler le contenu des fichiers

- Créer le fichier1.txt contenant "Bonjour !" et le fichier2.txt contenant "Je m'appelle <votre prénom>" et les mettre dans le dossier docs en utilisant la commande " cd docs/" puis on utilise la commande " echo Bonjour! > fichier1.txt " et " echo " Je m'appelle Daren" > fichier2.txt"

- Pour les concaténer on utilise la commande " cat fichier1.txt fichier2.txt > resultat.txt" et pour l'afficher on utilise la commande "cat resultat.txt"

- Pour ajouter une ligne à la fin sans effacer le contenu la commande est " echo "fin du test " >> resultat.txt "

- Pour copier le fichier resultat.txt et le coller on utilisera la commande " cp resultat.txt resultat_sauvegarde.txt"

## Étape 4 : Retrouver et quitter 

- ![alt text](image-2.png) comme on peut le voir on utilise la commande history pour voir les anciennes commandes.

- Pour retrouver une commande sans la taper on peut utiliser la flèche du bas ↓ et la flèche du haut ↑

- Pour retrouver les documents .py on utilise la commande "find station-meteo -name "*.py""

- Et pour quitter on utilise la commande "exit"