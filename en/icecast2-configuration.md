# Configure your Icecast 2 Server

## Handle JSON API Call

By default Icecast 2 will not provide a `status-json.xsl` file, and that's a bit problematic if you're looking to perform a GET request on your Icecast 2 server.

You need to update the `/etc/icecast2/icecast.xml` file

```
<http-headers>
    <header name="Access-Control-Allow-Origin" value="*" />
    <header name="Access-Control-Allow-Headers" value="*" />
    <header name="Access-Control-Allow-Methods" value="POST, GET, OPTIONS" />
</http-headers>
```

Do not forget to restart your icecast server after editing this configuration file.

You can now query the endpoint `/status-json.xsl` to get a JSON response including your current playing song.
