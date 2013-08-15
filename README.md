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

or more option

```
"spm": {
  "peaches": {
    "beautify": true, // 是否需要格式化输出,默认为 false
    "model":"alipay", // 指定上传图片到哪台服务器,默认支持 'alipay' , 'tfsdaily' ,默认为 alipay
    "retina":true,    // 是否支持高清显示,默认为 false
    "format":"png8",  // 输出图片的格式,支持 png8 和 png24 ,默认为 png8
    "sort":"h"        // 输出图片的排列规则, h 为竖排,v 为横排 默认为 h
  }
}
```

## Build

```
$ spm build
```

Then check `dist/file.css`, it contains the sprites images that peaches make for you.
