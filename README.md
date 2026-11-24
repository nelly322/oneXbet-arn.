# oneXbet-arn — prototype source v0.3

Base Expo / React Native, pas un APK final.

Inclus : écran d’accès provisoire, sélecteur 1xBet / BetWinner / MelBet / WINWIN, matchs fictifs, favoris, coupon combiné, calcul indicatif, historique local, formulaire local d’ajout de match.

Non inclus : vraies cotes, flux de scores, connexion aux comptes bookmakers, dépôts/retraits, pari réel, backend, base SQLite d’administration. Ces fonctions nécessitent des fournisseurs autorisés, des clés côté serveur et des tests.

Démarrage : installer Node.js LTS, lancer `npm install`, puis `npx expo start`.

Sécurité : l’écran accepte toute saisie de 4 caractères ou plus. Remplacer par une authentification serveur avant diffusion. Ne jamais intégrer un mot de passe ou une clé API dans l’APK. Les données visibles sont fictives.