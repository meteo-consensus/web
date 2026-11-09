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

© 2026 Les contributeurs de Météo Consensus. Tous droits réservés.

Le code et les contenus du site ne sont pas sous licence libre : le dépôt est public, mais toute réutilisation est soumise à une autorisation préalable. C'est pourquoi `package.json` déclare `"license": "UNLICENSED"` et le dépôt ne contient pas de fichier `LICENSE`. Les demandes d'autorisation se font en ouvrant une issue sur https://github.com/meteo-consensus/web/issues.

Cette mention couvre le code et les contenus propres au site, pas les données issues des sources tierces (Météo-France, Open-Meteo et les producteurs des modèles) : ces données gardent leurs propres licences et doivent être accompagnées de leurs mentions d'attribution, par exemple « Données Météo-France » avec la date de dernière mise à jour, ou « Weather data by Open-Meteo.com » avec les crédits des modèles.
