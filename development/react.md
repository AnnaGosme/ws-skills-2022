# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ❌ / ✔️
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️
import { Dispatch, SetStateAction } from "react";
import { deleteSkill } from "../services/skills";
import { ISkillsDisplay } from "../types/ISkill";
import styles from "../pages/SkillsPage.module.css";

interface SkillsProps {
  skill: ISkillsDisplay;
  setSkills: Dispatch<SetStateAction<ISkillsDisplay[]>>;
}

export default function SkillDisplay({ skill: {id, name}, setSkills }: SkillsProps) {
  const handleDelete = 
   async () => {
    try {
      console.log(id)
 
      setSkills((oldList) => oldList.filter((skill) => skill.id !== id));
      await deleteSkill(id);
    } catch (err) {
      console.error(err);
    }
  };

  return (
    <>
      <section >
        <h3>{name}</h3>
        <button onClick={() => handleDelete()}>Delete</button>
      </section>
    </>
  );
}

### Utilisation dans un projet ❌

[lien github](...)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description :stage 6 mois de Dev front chez Deezer

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
