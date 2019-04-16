# Add the Current Song on your WebRadio Page with the POST Webhook method

## Enable the POST Webhook method

### Start Configuration
On your [WebRadios listing page](/my/radio), click on the arrow at on the top right of your WebRadio panel and click on "Edit Current Song System"

![WebRadio Panel Settings](/guides/api-fetcher-001.png "WebRadio Panel Settings")

You'll see we provide a certain number of mechanisms to get the current song from your WebRadio. Let's see the POST Webhook method.

![Api fetcher method](/guides/api-fetcher-002.png "POST Webhook method")

This system is made for the webradio owners that use very specific softwares for streaming their audio stream. Some of those softwares allow to execute a specific script each time a new song is played.

You can configure your software to talk to webradio.io and tell us you're playing a new song.

### Configure Your Software
You will have to refer to the documentation of your software to check how to perform HTTP POST Requests.

Once you're ready to test your POST Request, click the "Try" button.

### Try... we're listening...

We are now listening for your requests. Leave the tab / window open and go to your software to execute the request.

If everything is correctly configured, you should see the song data (artist and title) appearing on the white box.

### Validate the result
You finally see an example of the result. If something is incorrect, you can change your software settings until the result works as expected.

If what you see is correct, click on the big "Confirm" button and you're good to go !

### You're done !

Congratulations !
