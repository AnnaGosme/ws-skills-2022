# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
// help catch mistakes early through a type system and to make JavaScript development more efficient
- les types de bases ✔️
// Boolean · Number · String · Array · Tuple · Enum · Unknown · Any.
- comment et pourquoi étendre une interface ✔️
// type checking focuses on the shape that values have. 
- les classes et les decorators ✔️

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
