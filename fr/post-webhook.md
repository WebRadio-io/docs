# Ajouter la musique en cours sur votre Page WebRadio Page grâce à la méthode POST Webhook

## Activer la méthode POST Webhook

### Démarrer la Configuration
Sur votre [liste de vos WebRadios](/my/radio), cliquez sur la petite flêche à droite de votre panneau WebRadio et cliquez sur "Modifier le système de musique en cours"

![WebRadio Panel Settings](/guides/api-fetcher-001.png "WebRadio Panel Settings")

Vous verrez que nous fournissons un certain nombre de mécanismes permettant d'afficher la musique en cours sur votre WebRadio. Nous allons passer en revue la méthode *POST Webhook*.

![Api fetcher method](/guides/api-fetcher-002.png "POST Webhook method")

Cette méthode a été créée pour les managers de webradio qui utilisent un logiciel spécifique pour streamer le flux audio de leur radio. Certains de ces logiciels permettent d'exécuter certains scripts lors d'événement particulier.

Dans notre cas, nous voulons que le logiciel exécute une requête HTTP lorsqu'une nouvelle musique est jouée.

Vous pouvez configurer votre logiciel pour communiquer avec notre plateforme et nous informer qu'une nouvelle musique doit être affichée.

### Configurer votre logiciel
Premièrement il vous faudra vous fier à la documentation de votre logiciel afin de créer un script pour exécuter une requête HTTP de type POST.

Lorsque votre script est prêt, vous pouvez cliquer le bouton "Essayer".

### Testez votre script... nous écoutons...

Une que vous avez cliqué sur le bouton "Essayer", nous commencerons à écouter les requêtes que vous aller nous envoyer.

Laissez cette fenêtre ouverte afin que notre script d'écoute continue à faire son travail. Allez sur votre logiciel de streaming et exécutez votre script (ou attendez qu'une nouvelle musique soit jouée).

Si tout est correctement configuré sur votre logiciel, vous devriez voir appraître les données (artiste et titre de la chanson) dans la petite case blanche.

### Valider le résultat
Une fois que le résultat correspond bien aux données de votre logiciel de streaming, vous pouvez sauvegarder la méthode POST Webhook.

Si tout est correct, cliquez sur le gros bouton "Confirmer" et tout est terminé!

### C'est bon !

Félicitations !
