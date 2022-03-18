[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com//https://U3284djfgiTGJVB/u0318-2.git)

```
addEventListener(
  "fetch", event => {
    let url = new URL(event.request.url);
    url.host = "appname.herokuapp.com";
    let request = new Request(url, event.request);
    event.respondWith(
      fetch(request)
    )
  }
)
```
