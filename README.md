
JPA & Hibernate
===

**Lundi**

veille sur TDD & ATDD

21.1 Dans votre projet BankOnline, ajouter les opérations pour les résultats suivant :
![center](/operations.png)

21.2 Veiller à bien distinguer versement et retrait par rapport à un virement :
![center](/dream.png)

21.3 Attention à gérer les cas particuliers telles que : pb de retrait/virement car solde insuffisant ou effectuer un virement d'un compte vers le même compte ou virement vers un compte inconnu... Pour ce faire, vous pouvez combiner le mécanisme des exceptions et les attributs de votre session.
![center](/soldeInsuffisant.png)

**Mardi**

veille sur OWASP / Cyber-sécurité

22.1 Nous souhaitons dorénavant distinguer un utilisateur d'un administrateur.
En effet, un utilisateur peut consulter un compte et son historique alors qu'un administrateur peut effectuer des opérations.

22.2 Gestion Log out de sorte que l'utilisateur soit déconnecté de l'interface, attention ici, il y a des soucis à gérer !
![center](/logout.png)

22.3 Deployer votre appli

**Mercredi**

veille sur JPA

23.1 Créer un "Projet ShopJpa" et ajouter une classe Article comme précédemment en n'oubliant pas un constructeur à 0 paramètre + un constructeur avec tous les paramètres + getter/Setter + toString

23.2 Ajouter un repertoire lib à votre projet et inserer toutes les dépendances hibernate (download hibernate release/zip + dans /hibernate-release-5.4.1.Final/lib/required/ -> copier les librairies + sous Eclipse/clic droit tous les Jars/add to build path (de même pour mariadb-java-client-2.4.1.jar + log4j-1.2-api-2.11.2.jar + log4j-core-2.11.2.jar)

23.3 Mettez en place le mapping de votre classe en utilisant javax.persistence

23.4 Ajouter un fichier de configuration Jpa en lien avec vos drivers jdbc dans un nouveau repertoire META-INF obligatoirement dans src

23.5 Tester en ajoutant un article puis afficher, modification d'un article puis afficher, suppression d'un article puis afficher pour vérification.

**Jeudi**

veille sur Hibernate

Préparation OPQUAST

Démarches de recherches de stages & alternances

**Vendredi**

veille sur JBoss, WebSphere, WebLogic, GlassFish

Préparation OPQUAST

Démarches de recherches de stages & alternances


**Ressources**

https://blog.apollossc.com/agile/lab-n1-tdd-atdd-bdd-cest-quoi-difference/

[OWASP](https://www.owasp.org/index.php/Main_Page)

[Hibernate. Everything data. - Hibernate](http://hibernate.org/)
