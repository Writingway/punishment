# Punition – Conventions de Commit GitHub
## Objectif
Avoir des messages de commit clairs, cohérents et utiles.  
Chaque commit doit dire ce qu’il fait, sans qu’on doive deviner.

---
## Format obligatoire
feat(api): add user login endpoint
Allow users to log in and get a JWT.
Closes #42

feat(api)!: remove old auth system
BREAKING CHANGE: old auth routes deleted

---
## Type   Quand l’utiliser
feat	    Nouvelle fonctionnalité
fix	      Correction de bug
docs	    Documentation uniquement
style     Formatage, indentation, espaces
refactor	Amélioration du code sans changer le comportement
test	    Ajout ou mise à jour de tests
build	    Changement de dépendance ou de configuration CI
chore	    Tâche mineure, maintenance
---
## Bonnes pratiques
Utiliser un verbe à l’impératif : “add”, “fix”, “remove”
Ne pas mettre de point à la fin
Un commit = une idée
Si tu touches plusieurs choses, fais plusieurs commits

