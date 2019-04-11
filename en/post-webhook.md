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

..

### Try... we're listening...
Now, you need to select the emplacement where the Artist name is displayed. You simply need to click once on the artist name.

![Json Artist Path](/guides/api-fetcher-004.png "Json Artist Path")

Next to the "Validate" Button you can see that we display the "JSON Path" to where the data is stored inside the data tree.
You can then click on Validate and do the exact same thing for the Title

Click a final time on "Validate"

### Validate the result
You finally see an example of the result. If something is incorrect, you can re-click on the "Try" button and start over.

![Confirmation Step](/guides/api-fetcher-005.png "Confirmation Step")

But if what you see is correct, click on the big "Confirm" button and you're good to go !

### You're done !
![Done !](/guides/api-fetcher-006.png "Done !")

Congratulations !
