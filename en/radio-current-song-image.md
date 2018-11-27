# WebRadio.io API - Get A Radio Current Artist Image

**For this to work, the given webradio owner must be a premium member.**

If a given WebRadio enabled one the Current Song Systems, and if his owner is a premium member, you will be able to query our server to retrieve the image of the artist being currently played on the webradio.

All you need is the WebRadio unique name (the one you can find in the URL of the webradio, after the `@` symbol).

For example, this is what the query will look like for our demo WebRadio "Pi":

`GET https://webradio.io/api/radio/pi/song/picture`

Just change "pi" with the ID of your own WebRadio and you will get a response containing an URL of the image.
