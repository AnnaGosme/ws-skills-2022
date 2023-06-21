# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
Typescript permet de rajouter une couche de protection par dessus le Javascript et offre des fonctionnalités du développement orienté objet (typage, interfaces, classes abstraites, encapsulation, inheritance)

- les types de bases ✔️
 Boolean · Number · String · Array · Tuple · Enum · Unknown · Any.

- comment et pourquoi étendre une interface ✔️
Pour importer les propriétés de cette interface. Cela aide à créer des composants petits et réutilisables.

- les classes et les decorators ✔️
  Une classe en termes de Programmation orienté objet est un modèle pour la création d’objets. Une classe encapsule les données de l’objet.
  Les décorateurs sont des fonctions capables d’étendre le comportement d’autres fonctions sans les modifier. Le Décorateur est donc une fonction      qui sera exécutée préalablement à la classe, et qui lui fournira du comportement additionel à celui que l’on a nous-même défini. On appelle          cela une fonction d’ordre supérieur.
  

## 💻 J'utilise

### Un exemple personnel commenté ✔️
import { Address } from "./Address.js";

export class Person {
  private _name: string;
  private _gender: string;
  private _address: Address;

  constructor(name: string, gender: string, address: Address) {
    this._name = name;
    this._gender = gender;
    this._address = address;
  }

  public get name(): string {
    return this._name;
  }

  public get gender() {
    return this._gender;
  }

  public get address() {
    return this._address;
  }

  public set name(name: string) {
    this._name = name;
  }

  public set gender(gender: string) {
    this._gender = gender;
  }

  public set address(address: Address) {
    this._address = address;
  }
}

const testAddressOne = new Address("Champs Elysée", "Paris", "75008");

export const testPersonOne = new Person("Bert", "M", testAddressFour);

Ici nous importons la classe Address dans le fichier de la class Person, car nous allons définir une class Person qui contiendra la classe Address. Une personne de class Person aura forcément un adresse de class Address. Ensuite nous créons une instance de la class Address, appelée testAddressOne, qui sera l'adresse de la nouvelle instance de Person, apellée testPersonOne. 

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
