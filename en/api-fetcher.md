# Add the Current Song on your WebRadio Page with the API Fetcher method

## Enable the API Fetcher method

### Start Configuration
On your [WebRadios listing page](/my/radio), click on the arrow at on the top right of your WebRadio panel and click on "Edit Current Song System"

![WebRadio Panel Settings](/guides/api-fetcher-001.png "WebRadio Panel Settings")

You'll see we provide a certain number of mechanisms to get the current song from your WebRadio. Let's see the API Fetcher method.

![Api fetcher method](/guides/api-fetcher-002.png "Api fetcher method")

### Try Your Endpoint
You see there's an input where you have to enter the URL of the API Endpoint that will provide the Artist and Title of your server' current song.

[If you're using Icecast2 you can check this tutorial.](/guide/icecast-2-configuration)

Copy paste the URL into the field input and click on the "Try" button on the right.

If your URL returns an error, you should see the error message displaying in red below.

But in case of success, you'll see a small confirmation
![Success](/guides/api-fetcher-003.png "Success")

### Select the data
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
