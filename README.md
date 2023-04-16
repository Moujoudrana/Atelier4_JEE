# Atelier4_JEE
Travail à faire:
Récupérer le code source de l'application non sécurisé qui permet de gérer les patients (résultat de l'activité pratique N°3). Le code source de cette application se trouve dans le repository suivant : https://github.com/mohamedYoussfi/unsecured-hospital-app.git.
Sécuriser cette application en intégrant un système d'authentification basé sur Spring security avec les trois stratégies : InMemoryAuthentication, JdbcAuthentication et UserDetailsService.
Vidéo à utiliser comme ressource principale : https://www.youtube.com/watch?v=7VqpC8UD1zM

Cette activité m'a permis de mettre en pratique la sécurité d'une application web en établissant un systeme d'authentification basé sur Spring security.
Les dépendances que j'ai utilisé sont Spring Web et le moteur de template Thymeleaf, Spring data JPA, Lombok, Spring web, MySQL, Spring Boot DevTools et Spring Security. Ainsi que Bootstrap
   
      -Spring Data JPA fournit l’interface JpaRepository<T, ID> qui hérite de CrudRepository<T, ID> et qui fournit un ensemble de méthodes pour interagir avec une base de données relationnelle.
    
      -Lombok a pour but de générer à la compilation du code Java les getters, les setters, la methode toString, ainsi que les constructeurs avec ou sans parametre, à notre place. Tout se fait à l’aide de simples annotations poser dans les classes.
    
      -Spring Web permet de créer des applications Web basées sur Spring avec une configuration minimale.
      -Spring Web MVC est le module Spring consacré au développement d’application Web et d’API Web. Le nom de ce module renvoie directement au modèle MVC (Modèle Vue Contrôleur).

      -Thymeleaf est un template engine. Principalement conçu pour produire des vues Web, il fournit un support pour la génération de documents HTML, XHTML, JavaScript et CSS (voire de n’importe quel format texte).
  
      -MySQL est l'un des systèmes de bases de données relationnelles les plus populaires et il est souvent utilisé dans les applications Spring Boot.
  
      -Spring-boot-devtools : une dépendance Spring Boot qui fournit des outils de développement pratiques pour le développement de vos applications Spring Boot. (Le mécanisme de rechargement automatique des classes en mode développement)
  
      -Bootstrap: Une bibliothèque open-source de développement front-end pour la conception de sites et d'applications web.
  
Spring Security:
Spring Security est un Framework de sécurité léger qui fournit une authentification et un support d’autorisation afin de sécuriser les applications Spring. Il est livré avec des implémentations d’algorithmes de sécurité populaires.


-L'application a pour objectif de gerer les utilisateurs, grace au opération CRUD (Create, Read, Update, Delete). L'interface utilisateur se représente comme suit:

![image](https://user-images.githubusercontent.com/93864104/232344419-6caaa1d1-ba95-4fdc-bafc-3b27d488754e.png)

-L'administrateur a la possibilité de creer, modifier, visualiser et supprimer des utilisateurs.
SUPPRIMER:
![image](https://user-images.githubusercontent.com/93864104/232345084-486ff2db-e603-40bd-8204-f71e6c69787e.png)

MODIFIER:
![image](https://user-images.githubusercontent.com/93864104/232345115-f290ebe8-fe64-4d78-9607-40b9588f5a1d.png)

CREER:
![image](https://user-images.githubusercontent.com/93864104/232345135-1ef6e7fa-8351-4183-abaa-1cf938760a99.png)







