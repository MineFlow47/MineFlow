# Configuration

Ce dossier contient les fichiers de configuration du projet.

## Fichiers Typiques

- `database.config.js` - Configuration de la base de données
- `server.config.js` - Configuration du serveur
- `app.config.js` - Configuration de l'application
- `*.env.example` - Exemples de variables d'environnement

## Sécurité

⚠️ **Important** :
- Ne jamais commiter de fichiers `.env` contenant des secrets
- Utiliser des fichiers `.env.example` comme templates
- Stocker les secrets de production de manière sécurisée

## Structure Suggérée

```
config/
├── development/     # Config pour développement
├── staging/         # Config pour staging
├── production/      # Config pour production
└── .env.example     # Template de variables d'environnement
```

---

**Note** : Ce dossier est actuellement vide. Les configurations seront ajoutées selon les besoins.
