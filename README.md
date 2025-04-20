# SAÉ S1.01 – Gestion des absences
 ## 📋 Présentation

Ce projet a été réalisé dans le cadre du BUT1 Informatique. Il consiste à développer une application en ligne de commande permettant de gérer les absences des étudiants dans une formation universitaire. L’outil développé agit comme un interpréteur de commandes, capable de recevoir des instructions textuelles et de répondre automatiquement.

## 👥 Membres du binôme
Ce projet a été réalisé seul, par choix personnel.

## ⚙️ Fonctionnalités

Le logiciel permet d’enregistrer les étudiants d’un groupe, de noter leurs absences jour par jour et de gérer les justificatifs qui peuvent être déposés après une absence. Il prend en compte les délais de dépôt de justificatif, permet à l'utilisateur de valider ou non ces derniers, un historique structuré des absences est conservé avec leur statut (en attente, justifiée, non-justifiée, etc.).

Visualisation de la situation d’un étudiant, d'afficher la liste des étudiants avec leur nombre d’absences, ou encore d’identifier ceux qui dépassent la limite d’absences autorisées et deviennent donc "défaillants".

Le logiciel est entièrement personnalisable, le temps imparti pour justifier une absence et le nombre d'absences limites sont modifiables.

## 🛠️ Développement et Tests

Le développement est structuré en quatre sprints progressifs, chacun validé par des fichiers de test (commandes d’entrée et sortie attendue). Le code est commenté, testé, et suit les conventions de nommage vues en cours.

## 🧪 Structure du développement

Le développement a été découpé en **4 sprints**, chacun ajoutant de nouvelles fonctionnalités :

- **Sprint 1** : `inscription`, `absence`, `etudiants`, `exit`
- **Sprint 2** : + `justificatif`, `validations`, `validation`
- **Sprint 3** : + `etudiant`
- **Sprint 4** : + `defaillants`
