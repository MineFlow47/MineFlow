# Tests

Ce dossier contient tous les tests automatisés du projet.

## Structure Suggérée

```
tests/
├── unit/            # Tests unitaires
├── integration/     # Tests d'intégration
├── e2e/             # Tests end-to-end
└── fixtures/        # Données de test
```

## Types de Tests

### Tests Unitaires
- Tester les fonctions individuelles
- Isolation complète
- Rapides à exécuter

### Tests d'Intégration
- Tester les interactions entre modules
- Vérifier l'intégration avec la base de données
- Tester les appels API

### Tests End-to-End (E2E)
- Tester le flux complet de l'application
- Simuler le comportement utilisateur
- Cypress, Selenium, Playwright

## Bonnes Pratiques

- Maintenir une couverture de tests > 80%
- Écrire des tests avant de coder (TDD)
- Nommer les tests clairement
- Tester les cas limites et les erreurs

---

**Note** : Ce dossier est actuellement vide. Les tests seront ajoutés au fur et à mesure du développement.
