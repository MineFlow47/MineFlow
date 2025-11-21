# Guide de Contribution à MineFlow

## Bienvenue !

Merci de votre intérêt pour contribuer à MineFlow. Ce guide vous aidera à comprendre comment participer au développement du projet.

## Code de Conduite

- Soyez respectueux envers tous les contributeurs
- Acceptez les critiques constructives
- Concentrez-vous sur ce qui est meilleur pour la communauté
- Faites preuve d'empathie envers les autres

## Comment Contribuer ?

### 1. Signaler des Bugs

Si vous trouvez un bug :
1. Vérifiez qu'il n'a pas déjà été signalé dans les Issues
2. Créez une nouvelle Issue avec :
   - Un titre descriptif
   - Les étapes pour reproduire le bug
   - Le comportement attendu vs le comportement actuel
   - Captures d'écran si applicable
   - Votre environnement (OS, version du logiciel, etc.)

### 2. Proposer des Nouvelles Fonctionnalités

1. Ouvrez une Issue de type "Feature Request"
2. Décrivez clairement la fonctionnalité souhaitée
3. Expliquez pourquoi elle serait utile
4. Proposez une approche d'implémentation si possible

### 3. Contribuer au Code

#### Étape 1 : Fork et Clone

```bash
# Forker le repo sur GitHub, puis cloner votre fork
git clone https://github.com/VOTRE-USERNAME/MineFlow.git
cd MineFlow

# Ajouter le repo original comme remote
git remote add upstream https://github.com/MineFlow47/MineFlow.git
```

#### Étape 2 : Créer une Branche

```bash
# Synchroniser avec la branche principale
git checkout main
git pull upstream main

# Créer une nouvelle branche
git checkout -b feature/ma-nouvelle-fonctionnalite
```

#### Étape 3 : Faire vos Modifications

- Suivez les conventions de code du projet
- Écrivez des tests pour vos modifications
- Documentez votre code
- Faites des commits atomiques et descriptifs

#### Étape 4 : Tester

```bash
# Exécuter les tests
npm test  # ou python -m pytest, selon la partie du projet

# Vérifier le style de code
npm run lint  # ou pylint, flake8, etc.
```

#### Étape 5 : Commit

```bash
git add .
git commit -m "feat: ajouter la fonctionnalité X

Description détaillée de ce qui a été ajouté et pourquoi."
```

**Convention de nommage des commits** :
- `feat:` Nouvelle fonctionnalité
- `fix:` Correction de bug
- `docs:` Modifications de documentation
- `style:` Changements de formatage
- `refactor:` Refactoring de code
- `test:` Ajout ou modification de tests
- `chore:` Maintenance (dépendances, config, etc.)

#### Étape 6 : Push et Pull Request

```bash
# Pousser votre branche
git push origin feature/ma-nouvelle-fonctionnalite
```

Puis sur GitHub :
1. Créez une Pull Request depuis votre branche
2. Remplissez le template de PR avec :
   - Description des changements
   - Issues liées
   - Captures d'écran si applicable
3. Attendez la revue de code

### 4. Revue de Code

- Soyez ouvert aux suggestions
- Répondez aux commentaires
- Effectuez les modifications demandées
- Une fois approuvée, votre PR sera mergée !

## Standards de Code

### Style de Code

- **Python** : Suivre PEP 8
- **JavaScript** : Utiliser ESLint avec les règles du projet
- **Indentation** : 2 ou 4 espaces (selon le langage)
- **Noms de variables** : Descriptifs et en anglais/français selon contexte

### Documentation

- Commenter les parties complexes du code
- Mettre à jour la documentation technique
- Ajouter des docstrings pour les fonctions
- Maintenir le README à jour

### Tests

- Écrire des tests unitaires pour les nouvelles fonctionnalités
- Maintenir une couverture de tests > 80%
- Tester les cas limites et erreurs
- Ne pas casser les tests existants

## Structure du Projet

```
MineFlow/
├── src/               # Code source
│   ├── backend/       # API et logique métier
│   ├── frontend/      # Interface utilisateur
│   └── shared/        # Code partagé
├── docs/              # Documentation
├── tests/             # Tests automatisés
├── config/            # Configuration
└── scripts/           # Scripts utilitaires
```

## Processus de Release

1. Toutes les fonctionnalités sont testées sur `develop`
2. Après validation, merge vers `main`
3. Tag de version (semantic versioning)
4. Déploiement en production

## Questions ?

- Consultez la documentation dans `/docs`
- Ouvrez une Issue pour les questions générales
- Rejoignez notre canal de communication

## Remerciements

Merci pour vos contributions ! Chaque ligne de code, chaque bug signalé, et chaque suggestion compte.

---

**Ensemble, construisons MineFlow !** 💪
