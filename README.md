# peaches-example

---

The example for peaches in spm-alipay-suite.

---

## Prepare

```
$ npm install apm -g
```

## Config in your package.json

```
  "spm": {
    "peaches": true
  }
```

## Build

```
$ spm build
```

Then check `dist/file.css`, it contains the sprites images that peaches make for you.
