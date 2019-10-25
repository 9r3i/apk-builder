
[![Author](https://img.shields.io/badge/author-9r3i-lightgrey.svg)](https://github.com/9r3i)
[![License](https://img.shields.io/github/license/9r3i/apk-builder.svg)](https://github.com/9r3i/apk-builder/blob/master/license.txt)
[![Forks](https://img.shields.io/github/forks/9r3i/apk-builder.svg)](https://github.com/9r3i/apk-builder/network)
[![Stars](https://img.shields.io/github/stars/9r3i/apk-builder.svg)](https://github.com/9r3i/apk-builder/stargazers)
[![Issues](https://img.shields.io/github/issues/9r3i/apk-builder.svg)](https://github.com/9r3i/apk-builder/issues)
[![Release](https://img.shields.io/github/release/9r3i/apk-builder.svg)](https://github.com/9r3i/apk-builder/releases)


# APK Builder
- Actually, this library I prepared for AI, but I share it as well.
- Containing AI extension (ext.apk) that require two of valuable libraries.
- One is apkBuilder.ai, I build this myself.
- And the other one is apktools.
- The jar file, "apktool.jar", I get from here: https://github.com/iBotPeaches/Apktool
- Visit the apktool repository release to get new updates.
- This package requires JAVA, visit the official website for downloading the stuff: https://www.java.com/en/download/


# Installation
- For AI users, simply use command:

```
$ ai pkg addrepository 9r3i/apk-builder
$ ai install ext.apk
```


# Build an app
- For AI users, sample commands:

```
$ ai apk extract <path/to/file.apk>
$ ai apk build <path/to/directory>
$ ai apk sign <path/to/file.apk>
```

- Or using config file

```
$ ai apk prepare <path/to/directory>
$ ai apk execute
```

- Use ```$ ai apk help``` for more detail


