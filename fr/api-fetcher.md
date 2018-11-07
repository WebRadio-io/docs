# Ajouter la musique en cours sur votre Page WebRadio Page grâce à la méthode API

## Activer la méthode API

### Démarrer la configuration
Sur votre [liste de vos WebRadios](/my/radio), cliquez sur la petite flêche à droite de votre panneau WebRadio et cliquez sur "Modifier le système de musique en cours"

![WebRadio Panel Settings](/guides/api-fetcher-001-fr.png "WebRadio Panel Settings")

Vous verrez que nous fournissons un certain nombre de mécanismes permettant d'afficher la musique en cours sur votre WebRadio. Nous allons passer en revue la méthode API.

![Api fetcher method](/guides/api-fetcher-002-fr.png "Api fetcher method")

### Essayez votre URL
Dans le champ qui apparait vous devrez entrer l'URL de votre API qui permettra de récupérer le titre et l'artiste de la musique en cours sur votre serveur.

[Si vous utilisez Icecast 2 vous pouvez suivre ce rapide tutoriel.](/guide/icecast-2-configuration)

Collez l'URL dans le champ et cliquez sur le bouton "Essayer" à droite.

Si votre URL retourne un code erreur, vous devriez voir le message d'erreur s'afficher en rouge en dessous.

En cas de succès, vous verrez une petite confirmation.
![Success](/guides/api-fetcher-003.png "Success")

### Sélectionner les informations
Maintenant, vous devez sélectionner l'emplacement où le nom de l'artiste est affiché. Vous devez simplement cliquez une fois sur le nom de l'artiste.

![Json Artist Path](/guides/api-fetcher-004.png "Json Artist Path")

À gauche du bouton "Valider" vous verrez que nous affichons le "chemin JSON" indiquant où se trouve l'information à l'intérieur de l'arborescence des données.
Vous pouvez donc cliquer sur "Valider" et réitérer l'opération pour le titre de la musique.

Cliquez une dernière fois sur "Valider"

### Valider le résultat
Vous voyez enfin un exemple du résultat final. Si quelque chose n'est pas correct, vous pouvez recliquer sur "Essayer" et recommencer l'opération.

![Confirmation Step](/guides/api-fetcher-005.png "Confirmation Step")

Si tout est correct, cliquez sur le gros bouton "Confirmer" et tout est terminé!

### C'est bon !
![Done !](/guides/api-fetcher-006.png "Done !")

Félicitations !
