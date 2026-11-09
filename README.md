# web

Site : landing, démo en direct, documentation de l'API, pages par ville. Consomme l'API publique uniquement.

Part of [meteo-consensus](https://github.com/meteo-consensus): the weather API that crosses forecast models and learns which one is reliable where.

## Development

Requirements: Node.js (version in `.node-version`) and pnpm (version in `package.json`, `packageManager`).

```sh
pnpm install --frozen-lockfile
pnpm run check
```

## Licence

Tous droits réservés.

Le code et les contenus du site ne sont pas sous licence libre : le dépôt est public, mais toute réutilisation demande une autorisation. C'est pourquoi `package.json` déclare `"license": "UNLICENSED"` et le dépôt n'a pas de fichier `LICENSE`.

Cette mention couvre le code et les contenus propres au site, pas les données des sources : les données servies gardent leurs propres licences et mentions (« Données Météo-France », crédits des modèles, notices CC BY 4.0), affichées partout où elles sont servies.
