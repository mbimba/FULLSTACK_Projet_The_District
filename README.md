# FULLSTACK_Projet_The_District
Un nouveau restaurant souhaite mettre en place un site internet pour permettre à ses clients de commander en ligne.

Le site doit permettre d'afficher l'ensemble des plats ou de naviguer dans les catégories.

Le client doit pouvoir sélectionner un plat et passer une commande.

Lors de la commande, il doit indiquer ses nom et prénom, son adresse, sa ville, son numéro de téléphone et son email.

Le client reçoit un email de confirmation lorsque sa commande est validée.

La page contact doit permettre d'envoyer un message au restaurant via un formulaire.

Un plat est représenté par les informations suivantes :

    libelle
    description
    prix
    image
    catégorie
    active
Pour les stagiaires Full Stack
Créer la base de données

A partir de ce fichier sql, vous allez créer la base de données. Vous utiliserez l'outil de votre choix (phpmyadmin, heidisql, extension vscode ou phpstorm...) pour effectuer cette tâche.

Ensuite vous insérerez les données à partir des données fournies ci-dessous.

La table commande
La table categorie
La table plat

Réfléchissez à l'ordre d'insertion des données.

A la fin, vous effectuerez une sauvegarde complète de la base de données.
Ecrire des requêtes d'interrogation de la base de données

Vous devez écrire les requêtes suivantes:

    Afficher la liste des commandes ( la liste doit faire apparaitre la date, les informations du client, le plat et le prix )

    Afficher la liste des plats en spécifiant la catégorie

    Afficher les catégories et le nombre de plats actifs dans chaque catégorie

    Liste des plats les plus vendus par ordre décroissant

    Le plat le plus rémunérateur

    Liste des clients et le chiffre d'affaires généré par client (par ordre décroissant)

Ecrire des requêtes de modification de la base de données

    Ecrivez une requête permettant de supprimer les plats non actif de la base de données

    Ecrivez une requête permettant de supprimer les commandes avec le statut livré

    Ecrivez un script sql permettant d'ajouter une nouvelle catégorie et un plat dans cette nouvelle catégorie.

    Ecrivez une requête permettant d'augmenter de 10% le prix des plats de la catégorie 'Pizza'

Utiliser un langage coté serveur

Reprenez les pages que vous avez intégrées pour ajouter scripts serveurs. Toutes les pages doivent respecter la maquette et les bonnes pratiques.

Les requêtes SQL doivent être isolées dans des fonctions regroupées dans un fichier DAO.php. En utilisant PDO, vous écrirez une fonction pour chacune des requêtes dont vous avez besoin. Par exemple, pour obtenir la liste des catégories, vous pouvez écrire une fonction get_categories()`.

    Sur toutes les pages, vous devez faire apparaitre un header (incluant le menu) et un footer

    La page d'accueil doit afficher une barre de recherche, les catégories les plus populaires (6) et la liste des plats les plus vendus

    La page catégories doit afficher les catégories "actives" (afficher un nombre maximum de 6 catégories )

    La page plats doit afficher 6 plats avec le libellé, la description, le prix et un bouton qui permette de passer une commande.

    Suite à une commande, le client doit recevoir un email de confirmation reprenant les détails de sa commande. Pour envoyer le mail, utilisez la bibliothèque PHPMailer (vous retrouverez le tuto ici).

Mettre en ligne le site

A l'aide de la plate-forme d'hébergement amorce.org, vous publierez votre site web. Suivez les instructions de votre formateur.
RGPD

Ajoutez une page intitulée Politique de confidentialité et une page intitulée Mentions légales à votre site.
Les liens vers ces pages doivent être accessibles depuis n'importe quelle page.

La page de politique de confidentialité doit inclure, parmi d'autres informations, l'adresse mail de la personne responsable du traitement de données.
Vous trouverez des exemples sur internet, comme ici.

La page "Mentions légales" doit contenir des informations relatives à l'éditeur du site, l'hébergeur et le/la directeur/directrice de publication.


