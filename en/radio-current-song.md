# WebRadio.io API - Get A Radio Current Song

If a given WebRadio enabled one the Current Song Systems, you will be able to query our server to retrieve the current song being played, live.

All you need is the WebRadio unique name (the one you can find in the URL of the webradio, after the `@` symbol).

For example, this is what the query will look like for our demo WebRadio "Pi":

`GET https://webradio.io/api/radio/pi/current-song`

Just change "pi" with the ID of your own WebRadio and you will get a JSON response containing the current Artist and Song Title being played.
