<h1>Exercices de modélisation</h1>

Réalisez les MCD des applications suivantes selon leurs contraintes
<h3>I. LIVRES</h3>
----
Un auteur (nom, prénom, sexe, date de naissance) possède une bibliographie de livres (titre, date 
de sortie, nombre de pages, résumé). Il n'y aura pas de livres co-écrits dans la base de données. Un 
livre pourra posséder plusieurs genres (roman, fantastique, policier…).
----
<h3>II. ENTREPRISE</h3>
----
Une entreprise est représentée par une raison sociale, une adresse (+ cp / ville) et une date de 
création possède des salariés (nom, prénom, date de naissance, date d'embauche).
Un salarié peut posséder plusieurs types de contrat (CDI, CDD, intérim, ...) au sein de plusieurs 
entreprises (et plusieurs contrats au sein d’une même entreprise). Chaque type de contrat est 
unique. En cas de CDD, le salarié possède une date de fin de contrat (facultative si le salarié est en 
CDI).
----
<h3>III. E-COMMERCE</h3>
----
Un client (numéro de client, nom, prénom, adresse email, mot de passe, date d'inscription, 
coordonnées de votre choix) peut réaliser des commandes auprès d'un site e-commerce à une 
date donnée. Le site met en vente des produits (désignation, prix) appartenant à une catégorie
unique. Ceux-ci peuvent être commandés en de multiples exemplaires.
----
<h3>IV. FORUM</h3>
----
Vous êtes en charge de réaliser un forum. Celui-ci est constitué de sujets (ou topics) qui 
appartiennent à une catégorie unique. L'auteur du sujet (qui est un membre du forum) peut décider 
de verrouiller un sujet. Un sujet pourra évidemment contenir des messages (ou posts).
Les membres du forum se connectent au forum avec un identifiant (mail), possède un pseudo, un 
mot de passe et un rôle (celui-ci sera contenu dans un tableau dans l'entité membre). On pourrait 
retrouver plusieurs rôles prédéfinis : Admin, modérateur ou membre 'classique' par exemple# Exo-Mod-lisation
