# GraphQL

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL  ✔️
- les besoins auxquels répond GraphQL ✔️
- la définition d'un schéma
A schema is like a contract between the server and the client. It defines what a GraphQL API can and can't do, and how clients can request or change data. It's an abstraction layer that provides flexibility to consumers while hiding backend implementation details.
- Query ✔️
Declarative approach to asking for the data you want => fetches data – like a GET in rest
- Mutations change data – like a DELETE or a POST in REST ✔️
- Subscription ✔️
Sends data to its clients when a specific event happens

## 💻 J'utilise

### Un exemple personnel commenté ✔️
Un schema => Query

const typeDefs = gql`
  type Query {
    "Query to get tracks array for the homepage grid"
    tracksForHome: [Track!]!
    track(id: ID!): Track
  }


### Utilisation dans un projet ❌

[lien github](...)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- https://www.apollographql.com/tutorials/
- learning path pour obtenir certification Apollo graphql

## 🚧 Je franchis les obstacles

### Point de blocage ✔️

Description: Prise en main compliquée pour comprendre le fonctionnement et l'utilisation du language

Plan d'action : (à valider par le formateur)

- action 1 ✔️
Suivre le learning path proposé dans la doc
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌
- J'ai fait une [présentation](...) ❌
