# actix-sse
Example of server-sent events, aka `EventSource`, with actix web.

```sh
cargo run
```

Open http://localhost:8080/ with a browser, then send events with another HTTP client:

```sh
curl localhost:8080/broadcast/my_message
```

*my_message* should appear in the browser with a timestamp.
