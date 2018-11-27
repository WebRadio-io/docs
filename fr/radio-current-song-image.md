# WebRadio.io API - Image de l'Artiste en cours

**Cette fonctionnalité n'est disponible que si le gérant de la webradio est un membre premium.**

Si une WebRadio a activé son système de musique en cours, et si son gérant est un membre premium, vous serez en mesure d'effectuer un appel HTTP à notre API publique pour recevoir une image de l'artist de la musique actuellement jouée sur la WebRadio.

Tout ce dont vous avez besoin est du nom unique de la WebRadio (autrement appelé son ID). Vous le trouvez dans l'url d'une webradio, après le symbole `@`.

Voici un example d'appel HTTP pour notre WebRadio de Demo "Pi"

`GET https://webradio.io/api/radio/pi/song/picture`

Changez simplement "pi" avec l'ID de votre WebRadio et vous recevrez une réponse contenant l'image de l'artiste.
