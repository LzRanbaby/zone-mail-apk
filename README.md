# Zone Mail APK

把自建邮箱 Zone Mail（Cloud Mail）打包成安卓 App。

- 壳子就是一个 WebView，打开的是测试站 **https://zone-mail-test.liziran254.workers.dev**（v3.5.0 新版界面 + 翻译功能）。
- 正式版切过去之后，把 `android/app/src/main/java/com/zonemail/app/MainActivity.kt` 里的地址改成正式站再重新打包。
- 图标用的是新版玻璃砖邮箱图标（mail-pwa.png）。

## 打包

推到 `main` 分支或在 Actions 里手动点 Run，自动构建并发布到 Release（latest），下载 `zone-mail.apk` 安装即可。
