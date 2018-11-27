# WebRadio.io API - Musique en cours

Si une WebRadio a activé son système de musique en cours, vous serez en mesure d'effectuer un appel HTTP à notre API publique pour retrouver la musique actuellement jouée sur la WebRadio.

Tout ce dont vous avez besoin est du nom unique de la WebRadio (autrement appelé son ID). Vous le trouvez dans l'url d'une webradio, après le symbole `@`.

Voici un example d'appel HTTP pour notre WebRadio de Demo "Pi"

`GET https://webradio.io/api/radio/pi/current-song`

Changez simplement "pi" avec l'ID de votre WebRadio et vous recevrez une réponse JSON contenant l'artiste et la musique en cours.
