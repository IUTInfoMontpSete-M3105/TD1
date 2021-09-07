# <img src="ressources/logo.jpeg" width="17%" style="margin:auto;display:block;"/> Conception et Programmation Objet Avancées 
### IUT Montpellier-Sète – Département Informatique
* **Cours:** [M3105](https://github.com/IUTInfoMontpSete-M3105/Ressources)
* **Enseignants:** [Gaelle Hisler](mailto:gaelle.Hisler@umontpellier.fr), [Nadjib Lazaar](mailto:nadjib.lazaar@umontpellier.fr) (responsable), [Sophie Nabitz](mailto:sophie.nabitz@univ-avignon.fr), [Simon Robillard](mailto:simon.robillard@umontpellier.fr) 
* [Fiche TD1](TD1.pdf).

* Lien classroom : https://classroom.github.com/a/hzso_Cia

### Prise en main des outils
Tous les TDs de CPOA seront hébergés dans l'organisation GitHub du module :

https://github.com/IUTInfoMontpSete-M3105

Le schéma de travail sera le suivant :
1. Si ce n'est pas encore fait au semestre précédent, demandez le [StudentPack](https://education.github.com/pack) de GitHub. Vous obtiendrez la licence gratuite pour plusieurs outils payants et notamment la possibilité d'avoir des **projets privés** sur GitHub.
2. Dans le dépôt de chaque TD, un lien **GitHub Classroom** vous permet de créer un fork du projet et d'affecter automatiquement votre projet à l'organisation *IUTInfoMontpSete-M3105*. Ce qui permet aux enseignants d'être admins sur votre projet. L'adresse de votre fork sera :
 https://github.com/IUTInfoMontpSete-M3105/TD1-VotreLogin
 
    La commande pour le cloner en local (le télécharger sur votre machine) :

    `~/CPOA$ git clone https://github.com/IUTInfoMontpSete-M3105/TD1-VotreLogin`

3. Ensuite, pour travailler **localement** vous allez utiliser **Git** pour suivre l'évolution de votre travail. Vérifiez d'abord que votre configuration locale est correcte en ouvrant le fichier `.gitconfig` de votre `$HOME`. Votre configuration devrait rassembler à cela :
    ```
    [user]
    username = prenom-nom
    name = Prenom Nom
    email = prenom.nom@etu-umontpellier.fr
    ```
   
4. Pour chaque changement dans votre dépôt local que vous compter enregistrer, vous ferrez : 
    ```
    ~/CPOA/TD1-VotreLogin$ git add lEnsembleDeFichiersQueVousSouhaitezSuivre
    ~/CPOA/TD1-VotreLogin$ git commit -m "leMessagePourExpliquerLaSauvegarde"
    ```

    **Conseil :** Privilégiez des petits commits (un par question).
    
5. À la fin de votre travail, n'oubliez pas de pousser vos changements sur le dépôt distant.

La documentation concernant Git, ainsi que les transparents du cours, sont accecible dans [ce dépôt](https://github.com/IUTInfoMontpSete-M3105/Ressources).


