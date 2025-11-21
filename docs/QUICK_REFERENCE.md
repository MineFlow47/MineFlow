# Guide de Référence Rapide - MineFlow

## 🎯 Démarrage en 5 Minutes

### 1. Cloner le Projet
```bash
git clone https://github.com/MineFlow47/MineFlow.git
cd MineFlow
```

### 2. Explorer la Structure
```bash
ls -la
# Vous verrez : src/, docs/, tests/, config/, scripts/
```

### 3. Lire la Documentation
- Nouveau ? → [GETTING_STARTED.md](../GETTING_STARTED.md)
- Contribuer ? → [CONTRIBUTING.md](../CONTRIBUTING.md)
- Questions ? → [FAQ.md](FAQ.md)

## 📚 Liens Rapides de Documentation

| Document | Description |
|----------|-------------|
| [README.md](../README.md) | Vue d'ensemble du projet |
| [GETTING_STARTED.md](../GETTING_STARTED.md) | Guide pour débuter dans le développement |
| [CONTRIBUTING.md](../CONTRIBUTING.md) | Comment contribuer au projet |
| [docs/ARCHITECTURE.md](ARCHITECTURE.md) | Architecture technique |
| [docs/ROADMAP.md](ROADMAP.md) | Feuille de route du projet |
| [docs/FAQ.md](FAQ.md) | Questions fréquentes |
| [LICENSE](../LICENSE) | Licence MIT |

## 🛠️ Commandes Git Essentielles

### Configuration Initiale
```bash
# Configurer votre identité
git config --global user.name "Votre Nom"
git config --global user.email "votre@email.com"

# Cloner le repo
git clone https://github.com/MineFlow47/MineFlow.git
```

### Workflow Quotidien
```bash
# Voir les changements
git status
git diff

# Créer une branche
git checkout -b feature/ma-fonctionnalite

# Commiter les changements
git add .
git commit -m "Description des changements"

# Pousser vers GitHub
git push origin feature/ma-fonctionnalite

# Mettre à jour depuis main
git checkout main
git pull origin main
```

### Synchronisation
```bash
# Récupérer les dernières modifications
git fetch origin
git pull origin main

# Voir l'historique
git log --oneline -10

# Voir les branches
git branch -a
```

## 📁 Structure du Projet

```
MineFlow/
│
├── src/                    # Code source
│   ├── backend/           # API et logique serveur
│   ├── frontend/          # Interface utilisateur
│   └── shared/            # Code partagé
│
├── docs/                   # Documentation
│   ├── ARCHITECTURE.md    # Architecture système
│   ├── ROADMAP.md         # Feuille de route
│   ├── FAQ.md             # Questions fréquentes
│   └── QUICK_REFERENCE.md # Ce guide
│
├── tests/                  # Tests automatisés
│   ├── unit/              # Tests unitaires
│   ├── integration/       # Tests d'intégration
│   └── e2e/               # Tests end-to-end
│
├── config/                 # Configuration
│   └── [environnements]   # dev, staging, prod
│
├── scripts/                # Scripts utilitaires
│   └── [outils divers]    # setup, deploy, etc.
│
├── README.md              # Documentation principale
├── GETTING_STARTED.md     # Guide débutant
├── CONTRIBUTING.md        # Guide contribution
├── LICENSE                # Licence MIT
└── .gitignore            # Fichiers à ignorer
```

## 🚀 Prochaines Étapes

### Si vous êtes Nouveau en Programmation
1. ✅ Lire [GETTING_STARTED.md](../GETTING_STARTED.md)
2. ✅ Installer Git et un éditeur
3. ✅ Apprendre les bases (HTML, CSS, JavaScript ou Python)
4. ✅ Suivre un tutoriel en ligne
5. ✅ Revenir contribuer !

### Si vous êtes Développeur
1. ✅ Lire [CONTRIBUTING.md](../CONTRIBUTING.md)
2. ✅ Forker et cloner le repo
3. ✅ Choisir une issue "good first issue"
4. ✅ Créer une branche et coder
5. ✅ Soumettre une Pull Request

### Si vous êtes Gestionnaire/Chef de Projet
1. ✅ Lire [docs/ROADMAP.md](ROADMAP.md)
2. ✅ Consulter [docs/ARCHITECTURE.md](ARCHITECTURE.md)
3. ✅ Participer aux discussions sur GitHub
4. ✅ Définir les priorités et besoins

## 💡 Conseils Pro

### Développement
- 🔍 **Commiter souvent** : Petits commits réguliers > gros commits rares
- 📝 **Messages clairs** : `feat:`, `fix:`, `docs:` pour catégoriser
- ✅ **Tester avant commit** : Toujours vérifier que ça fonctionne
- 🔄 **Synchroniser régulièrement** : Pull souvent pour éviter les conflits

### Collaboration
- 💬 **Communiquer** : Poser des questions, c'est normal !
- 👁️ **Lire les discussions** : Beaucoup d'infos dans les issues
- 🤝 **Aider les autres** : Répondre aux questions, reviewer le code
- 🎯 **Rester focus** : Une fonctionnalité à la fois

### Apprentissage
- 📖 **Lire le code** : Apprendre en lisant les contributions
- 🔨 **Pratiquer** : Le meilleur apprentissage est la pratique
- 🐛 **Debugger** : Les erreurs sont des opportunités d'apprendre
- 🚀 **Partager** : Expliquer = comprendre mieux

## 📞 Besoin d'Aide ?

| Type | Où aller |
|------|----------|
| 📖 Questions générales | [FAQ.md](FAQ.md) |
| 🐛 Bug trouvé | [GitHub Issues](https://github.com/MineFlow47/MineFlow/issues) |
| 💡 Idée/Suggestion | [GitHub Discussions](https://github.com/MineFlow47/MineFlow/discussions) |
| 🤔 Demande de fonctionnalité | [GitHub Issues](https://github.com/MineFlow47/MineFlow/issues) (Feature Request) |

## 🎓 Ressources Externes

### Apprendre à Coder
- [freeCodeCamp](https://www.freecodecamp.org/) - Cours interactifs gratuits
- [Codecademy](https://www.codecademy.com/) - Cours pour débutants
- [MDN Web Docs](https://developer.mozilla.org/fr/) - Documentation web

### Apprendre Git
- [Git Book](https://git-scm.com/book/fr/v2) - Guide complet en français
- [Learn Git Branching](https://learngitbranching.js.org/?locale=fr_FR) - Tutoriel interactif
- [GitHub Docs](https://docs.github.com/fr) - Documentation GitHub

### Langages Spécifiques
- **Python** : [Python.org](https://docs.python.org/fr/3/)
- **JavaScript** : [javascript.info](https://javascript.info/)
- **React** : [React.dev](https://react.dev/)
- **Vue** : [Vue.js](https://vuejs.org/)

## 🔑 Raccourcis Clavier (VS Code)

| Action | Windows/Linux | macOS |
|--------|---------------|-------|
| Palette de commandes | `Ctrl+Shift+P` | `⌘+Shift+P` |
| Rechercher fichier | `Ctrl+P` | `⌘+P` |
| Rechercher texte | `Ctrl+Shift+F` | `⌘+Shift+F` |
| Terminal | `Ctrl+`` | `⌘+`` |
| Sauvegarder | `Ctrl+S` | `⌘+S` |

---

**Gardez ce guide sous la main !** 📌

*Dernière mise à jour : Novembre 2025*
