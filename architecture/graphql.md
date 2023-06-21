# GraphQL

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL  ✔️
La différence la plus notable entre REST et GRAPHQL est dans la manière dont les données sont envoyées au client par le serveur. Dans une architecture REST le client envoie une requête HTTP et le serveur envoie une réponse HTTPn alors qu'en GRAPHQL le client effectue une requête de données par une *query*.

- les besoins auxquels répond GraphQL ✔️
    - Récupère uniquement la donnée demandée : pas de over-fetching / under-fetching
    - Unifie et cache la complexité d’une architecture en micro-services : la communication entre les micro-services est fusionnée en un seul schéma        GraphQL.
    - Rapide et sécurisé : demande moins de ressources et de temps pour récupérer les données (car pas de over-fetching), le serveur retourne une           forme sécurisée, facile à lire et prévisible.

- la définition d'un schéma
A schema is like a contract between the server and the client. It defines what a GraphQL API can and can't do, and how clients can request or change data. It's an abstraction layer that provides flexibility to consumers while hiding backend implementation details.
Un schéma peut être considéré comme un contrat de communication entre le serveur et le client. Il définit ce que l'API peut et ne peut pas faire, comment les clients peuvent demander ou modifier les données de la base de données. Le schéma est une couche d'abstraction qui offre une flexibilité d'utilisation tout en cachant les détails de l'implémentation du côté back de l'application. 

- Query ✔️
Une *query* GRAPHQL est la méthode utilisée pour lire ou pour récupérer des données. Une mutation est utilisée pour écrire ou modifier des données. Dans les deux cas, l'opération est une simple chaîne de caractères que le serveur GRAPHQL parse et auquel il répondra en envoyant des données dans un format précis. Le format de réponse le plus commun en développement web et mobile est le JSON.

- Mutations ✔️
  voir ci-dessus
  
- Subscription ✔️
Une *subscription* est une opération GRAPHQL qui permet de s'abonner à un évènement sur le serveur. Le client recevra alors des mises à jour en temps réél du serveur à chaque fois que l'évènement auquel il est souscrit a lieu. Un évènement peut représenter une insertion, une modification ou une suppression de donnée. 

## 💻 J'utilise

### Un exemple personnel commenté ✔️

{
  hero {
    name
    friends {
      name
    }
  }
}

Ici nous effectuons une *query* pour obtenir des informations sur un objet "hero". Nous demandons en premier lieu le nom du hero. 
Nous pouvons également effectuer une sous-séléction des champs de l'objet. Les *queries* GRAPHQL peuvent traverser des objets connexes et leurs champs, permettant ainsi aux clients de récupérer des données connexes dans une seule et même requête, plutôt que de devoir effectuer de multiples requêtes comme dans une architecture REST classique. 


### Utilisation dans un projet ✔️

[lien github](https://github.com/WildCodeSchool/2209-wns-adleman-mapado/blob/main/client/src/gql/deletePoi.gql)

Description : Dans le projet Mapado, nous nous servons de gql pour construire nos *queries* et nos mutations GRAPHQL. Ici, un exemple de la mutation utilisée pour supprimer un point d'intérêt de l'application. 

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel  ✔️ ❌ 

Description : En milieu professionnel, la notion de subscriptions est utilisée, mais il ne s'agit pas de GRAPHQL car la plateforme 3DEXPERIENCE fonctionne avec un système propre à lui écrit par Dassault. Nous utilisons des webservices pour souscrire à des évènements afin que les widgets exposés sur un même dashboard soient à l'écoute des modifications effectuées dans chacun d'eux, et donc que l'ensemble du dashboard soit maintenu à jour (document qui change de statut par exemple). 

## 🌐 J'utilise des ressources

### Titre

- https://www.apollographql.com/tutorials/
- learning path pour obtenir certification Apollo graphql

## 🚧 Je franchis les obstacles

### Point de blocage ✔

Description: Prise en main compliquée pour comprendre le fonctionnement et l'utilisation du language

Plan d'action : (à valider par le formateur)

- action 1 ✔️
Suivre le learning path proposé dans la doc
- action 2 ❌ / ✔️
- ...

Résolution : Obtention du certificat Apollo certified Graph Developer Associate (21/10/2022)

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌
- J'ai fait une [présentation](...) ❌
