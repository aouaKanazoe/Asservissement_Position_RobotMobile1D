# 📌 Projet d'Asservissement en Position d'un Robot Mobile (1D)

## 🔧 Description

Ce projet vise à développer un système d’asservissement en position pour un robot mobile évoluant sur une seule dimension (1D). Le but est de concevoir et implémenter des lois de commande permettant au robot d’atteindre et de maintenir des positions cibles avec précision, en tenant compte de différentes spécifications techniques.

L'automatique constitue le cœur du projet. Elle est chargée de la modélisation du système, de la conception des lois de commande, et de la validation des performances à travers des simulations.

---

## 🎯 Objectifs

- Concevoir des lois de commande répondant à **deux cahiers des charges distincts**.
- Implémenter ces lois sur un simulateur et un système réel.
- Comparer les performances obtenues pour chaque solution proposée.
- 
---

## 📄 Cahiers des charges

### 📘 Cahier des charges 1

- Stabilité : oui
- Erreur statique : 10%
- Erreur de traînage : aucune
- Temps de réponse ≤ 5 s
- Dépassement : aucun
- consigne : 1m.
  
### 📘 Cahier des charges 2

- Stabilité : oui
- Erreur statique : 0%
- Erreur de traînage : 0.1
- Temps de réponse ≤ 4 s
- Dépassement : 5% max
- consigne: 25 cm.

---

## ⚙️ Contenu du projet

- `modeles/` : Modèles dynamiques du robot
- `commandes/` : Lois de commande (P, PI, D.)
- `simulations/` : fichiers de simulation Simulink
- `resultats/` : Résultats des simulations et analyses


## 🧪 Technologies utilisées

- MATLAB / Simulink 
- Contrôleur (PID,P,PI,D)

---

## 🧠 Contributions

- **Automatique** : Modélisation, analyse de stabilité, conception des correcteurs
- **Simulation** : Implémentation des lois de commande et visualisation

---

## 🚀 Pour démarrer

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/robot-1d-asservissement.git
