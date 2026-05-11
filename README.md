# LAB14-Bypass-Root-Detection-sur-Android-Techniques-Dynamiques-avec-Frida-Objection-et-Hooks-Natif


APK : UnCrackable-Level1.apk

Étape 1 — Démarrage et repérage du package

1. Lancement de frida-server: 
<img width="958" height="468" alt="image" src="https://github.com/user-attachments/assets/a3ed8478-f3d1-4228-99c8-b27171e21063" />

2. Vérification que l’appareil est visible:
 
<img width="1165" height="566" alt="image" src="https://github.com/user-attachments/assets/ecf2d5d5-a305-4913-ace1-075a1b219081" />

Étape 2 — Script Frida (bypass Java) prêt à l’emploi

<img width="1900" height="532" alt="image" src="https://github.com/user-attachments/assets/109f20ff-e4c4-4a96-9bf5-9eb5da5d201d" />

✅ L'app est ouverte et affiche un champ texte → le bypass root a fonctionné !

<img width="558" height="847" alt="image" src="https://github.com/user-attachments/assets/ba96c8cf-2bff-474b-81af-3faf8abeec38" />


Étape 3 — Ajouter des hooks natifs

<img width="1092" height="511" alt="image" src="https://github.com/user-attachments/assets/ded66d7c-d245-4638-a518-e8642a90893d" />

Étape 4 —  Même chose avec Objection

1 — Installer Objection

<img width="1920" height="947" alt="image" src="https://github.com/user-attachments/assets/970ab304-6719-4e16-8f2f-937709b03d5a" />


Vérifications:

  
<img width="1563" height="995" alt="image" src="https://github.com/user-attachments/assets/4926c5c7-b7c3-4aa0-ad90-18fde53bb0d1" />

2 — Préparer l’appareil et démarrer frida-server

a. Lancement de frida-server: 
<img width="958" height="468" alt="image" src="https://github.com/user-attachments/assets/a3ed8478-f3d1-4228-99c8-b27171e21063" />

b. Vérification que l’appareil est visible:
 
<img width="1165" height="566" alt="image" src="https://github.com/user-attachments/assets/ecf2d5d5-a305-4913-ace1-075a1b219081" />


3 — Démarrer Objection sur l’app cible


<img width="1517" height="912" alt="image" src="https://github.com/user-attachments/assets/ad249eec-05c9-4195-b1e4-d7817b979822" />


Étape 5 — Avec Medusa

1 — Installer Medusa (outil d’instrumentation)

Clonage de la boîte à outils Medusa et installation des dépendances Python:

<img width="962" height="688" alt="image" src="https://github.com/user-attachments/assets/f2c4dc0d-3acd-46e3-a708-61c6e470be95" />


2 — Lancer l’app avec Medusa et activer le module de bypass root

<img width="963" height="523" alt="image" src="https://github.com/user-attachments/assets/fff9e15e-31c3-4495-88d3-c59585f6933a" />

<img width="1900" height="997" alt="image" src="https://github.com/user-attachments/assets/f327d47e-5805-42c9-9deb-ffffdf60b322" />
