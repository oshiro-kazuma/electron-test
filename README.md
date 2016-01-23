electron-test
==============

<img src="https://raw.githubusercontent.com/oshiro-kazuma/electron-test/master/hello_electron.png" width="400">

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
$ electron-packager ./ electron-test --platform=darwin,win32 --arch=x64 --version=0.36.1
```
