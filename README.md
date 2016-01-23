electron-test
==============

![キャプチャ](https://raw.githubusercontent.com/oshiro-kazuma/electron-test/master/hello_electron.png "キャプチャ")

### setup ###

```bash
$ npm -g install electron
$ npm -g install electron-prebuilt
$ npm -g install electron-packager
```

### run ###

```bash
$ electron . 
```

### package ###

```
$ electron-packager ./ sample --platform=darwin,win32 --arch=x64 --version=0.36.1
```

