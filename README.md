# stuartgallery.com.au

Build dependencies for https://stuartgallery.com.au/

* hugo https://github.com/gohugoio/hugo/releases/latest
* firebase-tools `npm install -g firebase-tools`

Local development
```
$ hugo server -Dw
```

Build site
```
$ hugo
```

Deploy site
```
$ firebase deploy
```

You may need to login to firebase on first run
```
$ firebase login
```

You can go to the firebase console > hosting tom manage rollbacks.
