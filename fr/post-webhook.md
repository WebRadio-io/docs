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

We are now listening for your requests. Leave the tab / window open and go to your software to execute the request.

If everything is correctly configured, you should see the song data (artist and title) appearing on the white box.

### Validate the result
You finally see an example of the result. If something is incorrect, you can change your software settings until the result works as expected.

If what you see is correct, click on the big "Confirm" button and you're good to go !

### You're done !

Congratulations !
