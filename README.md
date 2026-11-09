# ClaudeUsage — versions publiées

Ce dépôt ne contient que les **versions publiées** de ClaudeUsage, app de barre de menus macOS
qui suit la consommation de ton quota Claude. Les sources ne sont pas publiques.

## Ce que fait l'app

- Les deux fenêtres de quota du compte Claude — **5 h** et **semaine** — en jauge, en
  pourcentage, ou les deux, directement dans la barre de menus.
- Une alerte avant d'épuiser une fenêtre, au seuil de ton choix.
- L'**état des services Claude** et les maintenances annoncées, avec une pastille dans la barre.
- La consommation locale de **Claude Code** sur ce Mac, par modèle et par projet.

## Installer

1. Télécharge le fichier `ClaudeUsage-<version>.dmg` de la dernière version, dans
   [Releases](../../releases/latest).
2. Ouvre-le et glisse **ClaudeUsage** dans le dossier **Applications**.
3. Premier lancement : macOS refuse d'ouvrir l'app, car elle n'est pas distribuée par l'App Store.
   Va dans **Réglages Système → Confidentialité et sécurité**, puis clique sur **Ouvrir quand même**.
4. ClaudeUsage te guide ensuite : la connexion de ton compte, les notifications, et deux réglages.

## Connecter ton compte

L'app lit ton quota avec un jeton que Claude Code fabrique pour toi, et qui reste dans le
trousseau de ton Mac. L'assistant de démarrage te donne la commande et te propose d'ouvrir le
Terminal ; rien n'est envoyé ailleurs qu'à l'API d'Anthropic.

## Configuration requise

macOS 15 ou plus récent, Mac à puce Apple.

## Mises à jour

Chaque version est publiée ici, avec sa note de version. L'app vérifie d'elle-même s'il en existe
une plus récente et te la propose — jamais sans te demander.
