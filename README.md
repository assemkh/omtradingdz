# OM TRADING

Site vitrine bilingue (français/anglais) d'OM TRADING, représentant ALPHA STONE en Algérie.

## Développement local

Le site est entièrement statique. Lancez un serveur HTTP depuis la racine du projet, par exemple :

```bash
python3 -m http.server 8080
```

Puis ouvrez `http://localhost:8080`.

## Déploiement Vercel

1. Dans Vercel, choisissez **Add New > Project**.
2. Importez le dépôt GitHub `assemkh/omtradingdz`.
3. Conservez **Framework Preset: Other**.
4. Laissez les commandes Build et Install vides, ainsi que le dossier de sortie par défaut.
5. Cliquez sur **Deploy**.

Le fichier `vercel.json` active les URL propres et la mise en cache longue durée des images statiques.
