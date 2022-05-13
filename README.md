# defi_4

Créer un repo privé ‘defi_4’ avec un fichier readme

Cloner le repo Créer une branche nommée ‘integration’
> git branch integration

Bascule sur votre nouvelle branche branche
> git checkout integration

Créer un fichier index.html
> touch index.html

Afficher les différences entre le fichier d’index et le commit HEAD actuel
> git status

Ajoute le contenu de fichiers à l’index
> git add .

Enregistrer les modifications dans le dépôt locale
> git commit -m "Ajout du fichier README et du fichier index.html" .

Mettre à jour les références distantes ainsi que les objets associés de votre nouvelle branche
> git push

Ajouter un paragraphe dans votre fichier index.html
Afficher les différences entre le fichier d’index et le commit HEAD actuel
> git status

Enregistrer les modifications dans le dépôt
> git commit -m "Ajout d'un paragraphe" index.html

Mettre à jour les références distantes ainsi que les objets associés sur la branche ‘intégration’
> git push

Ajouter un paragraphe dans votre fichier index.html
Afficher les différences entre le fichier d’index et le commit HEAD actuel
> git status

Enregistrer les modifications dans le dépôt
> git commit -m "Ajout d'un deuxième paragraphe" index.html

Mettre à jour les références distantes ainsi que les objets associés sur la branche ‘intégration’
> git push

Annuler votre dernier commit
> git log
> git reset --soft HEAD^

Basculer sur la branche main
> git pull

Fusionner la branche main avec votre branche ‘intégration’
> git merge integration

Afficher les différences entre le fichier d’index et le commit HEAD actuel
> git status
Enregistrer les modifications dans le dépôt
> git commit -m "Fusion de la branche integration à la branche main" .

Mettre à jour les références distantes ainsi que les objets associés sur la branche main
> git push

Supprimer la branche ‘intégration’ en locale et distante