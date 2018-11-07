# Configurez votre serveur Icecast 2

## Accepter les appels API

Par défaut Icecast 2 ne vous fournit pas d'URL `status-json.xsl`, et cela est problématique si vous voulez effectuer des requêtes GET sur votre serveur Icecast 2.

Vous devez commencer par mettre à jour le fichier de configuration `/etc/icecast2/icecast.xml`

```
<http-headers>
    <header name="Access-Control-Allow-Origin" value="*" />
    <header name="Access-Control-Allow-Headers" value="*" />
    <header name="Access-Control-Allow-Methods" value="POST, GET, OPTIONS" />
</http-headers>
```

N'oubliez pas de redémarrer votre serveur Icecast 2 une fois que le fichier de configuration soit changé.

Vous pouvez maintenant visiter l'url `/status-json.xsl` pour recevoir une réponse JSON incluant les informations de la musique en cours.
