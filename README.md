# Récepteur de webhooks Express

Un récepteur qui vérifie la signature des notifications entrantes.

Modèle de départ Bastide (`api-express-webhooks`), écrit par Glowsoft. Il se construit et se déploie sans modification ; la campagne hebdomadaire le construit avec des valeurs d'essai.

## Variables

Le déploiement en un clic les demande avant la construction ; copiez `.env.example` pour un essai local.

- `WEBHOOK_SECRET` (requise) : Le secret partagé avec l'émetteur, qui sert à vérifier chaque signature. À obtenir ici : https://docs.github.com/fr/webhooks/using-webhooks/validating-webhook-deliveries
