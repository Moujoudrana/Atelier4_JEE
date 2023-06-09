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


-L'application a pour objectif de gerer les utilisateurs, grace aux opération CRUD (Create, Read, Update, Delete).

-L'interface suivante permet à un utilisateur normal ou à un administrateur de se connecter:
![image](https://user-images.githubusercontent.com/93864104/232748965-39d0a713-4d0e-46f8-85b1-d60cbd35aea2.png)

-Un utilisateur connecté a la possibilité de visualiser les patients:
![image](https://user-images.githubusercontent.com/93864104/232750038-b5a6421f-9991-46ed-be36-aee0d3c7540e.png)

-Il est possible d'effectuer des recherches à partir des noms des patients:
![image](https://user-images.githubusercontent.com/93864104/232750754-018b252f-4a4a-48f5-acbb-33d4635bfde5.png)

-L'interface administrateur se presente comme suit:
![image](https://user-images.githubusercontent.com/93864104/232751247-5db531a5-63e5-4b20-aa00-df7d0250d18d.png)

-L'administrateur a la possibilité de creer, modifier, visualiser et supprimer des utilisateurs.

SUPPRIMER:
![image](https://user-images.githubusercontent.com/93864104/232754128-fe90033c-2606-4736-b6f5-8b303d2075b2.png)

-L'utilisateur avec l'id=6 est supprimé:
![image](https://user-images.githubusercontent.com/93864104/232754221-c1ecdb57-4501-4add-a3d0-9d1534e5d92d.png)

MODIFIER:
![image](https://user-images.githubusercontent.com/93864104/232755106-6def0b19-c243-4ab4-a975-ab67dccae31f.png)

![image](https://user-images.githubusercontent.com/93864104/232754830-036736ff-aa5a-4d9a-aed8-206332770185.png)

![image](https://user-images.githubusercontent.com/93864104/232798160-6134f737-0100-4223-a569-12769d67a6d1.png)

![image](https://user-images.githubusercontent.com/93864104/232798321-740b4d6a-6dff-4540-b3b9-7c606fe42951.png)

CREER:
![image](https://user-images.githubusercontent.com/93864104/232755609-709cb498-f4a7-4a49-821d-9f67733ff115.png)

![image](https://user-images.githubusercontent.com/93864104/232756127-76508815-3ee4-4897-ad09-08ebe9b8f898.png)

-L'ajout d'un nouveau patient Rana:
![image](https://user-images.githubusercontent.com/93864104/232756364-a15183cf-88c9-4bbc-8fd0-6334eb7882e3.png)

-Patient ajouté:
![image](https://user-images.githubusercontent.com/93864104/232798784-f262def4-0098-403f-9399-cfe9b6ef5dc0.png)




