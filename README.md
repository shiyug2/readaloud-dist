# ReadAloud 分发

`latest.json` 是 app 的更新清单。app 每次启动会读取这里,发现新版本就提示下载。

每发新版:
1. 在 Releases 里建一个 `vX.Y.Z` 的 release,上传 `ReadAloud-vX.Y.apk`
2. 把 `latest.json` 的 `latestVersion`、`apkUrl`、`notes` 更新成新版本

APK 通过 GitHub Releases 托管,下载链接永久有效。
