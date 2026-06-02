# 🛠️ Guide de Contribution - Écosystème Evolupp

Merci de l'intérêt que vous portez à Evolupp. Pour bâtir un écosystème technologique souverain et performant, nous appliquons des standards d'ingénierie stricts. 

Ce projet n'est pas un espace d'expérimentation désordonné. Chaque ligne de code intégrée doit être optimisée, documentée et justifiée. Avant de proposer une contribution par e-mail, merci de lire attentivement les directives ci-dessous.

---

## ❓ Comment nous aider ?

### Vous pouvez coder, trouver des idées, améliorer l'interface utilisateur, ou si vous trouvez 

## 🎯 Nos Critères d'Exigence

### 1. Zéro Dépendance Externe
Toute contribution au Core système ne doit dépendre d'aucune bibliothèque tierce, d'aucun framework lourd, ni d'éléments issus de Linux ou d'Android. Nous écrivons du code natif et pur.

### 2. Qualité du Code (Clean Code)
* **Lisibilité :** Le code doit être explicite. Les noms de variables et de fonctions doivent être clairs et transparents.
* **Documentation :** Chaque fonction complexe ou module basse couche doit inclure des commentaires expliquant le *pourquoi* de l'implémentation, et non simplement le *comment*.
* **Performance :** L'allocation de mémoire et les cycles CPU doivent être optimisés au maximum. Le code inutile ou redondant est systématiquement rejeté.

### 3. Standards des Messages de Validation (Commits)
Pour maintenir un historique clair, nous imposons la norme des *Conventional Commits*. Vos messages doivent adopter le format suivant :
`type(périmètre): description courte en minuscule`

* **feat :** Nouvelle fonctionnalité (ex: `feat(core): add keyboard driver logic`)
* **fix :** Correction d'un bug (ex: `fix(nav): resolve memory leak in webview`)
* **docs :** Modification de la documentation (ex: `docs(readme): update contact mail`)

---

## 📬 Processus de Soumission

Toutes les propositions se font actuellement par échange direct via l'adresse de l'équipe : **colin.gp@ikmail.com**.

### Pour une Idée ou un Design :
Envoyez un descriptif structuré expliquant le besoin, le problème ciblé et une ébauche de fonctionnement ou de visuel.

### Pour du Code :
1. Préparez un patch propre ou un accès à votre branche de travail.
2. Assurez-vous que votre code compile parfaitement dans l'environnement de test défini.
3. Joignez une description des tests de non-régression effectués.

*L'équipe Evolupp se réserve le droit de rejeter sans justification toute contribution ne respectant pas ces standards de rigueur.*
