# LumiCast 1.8.5

[简体中文](#简体中文) · [日本語](#日本語) · [English](#english)

## 简体中文

LumiCast 是一款面向 Android 电视、电视盒子、平板和手机的直播播放器，基于 [NativeWasmTv](https://github.com/buhanzhe/NativeWasmTv) 普通版独立构建。1.8.5 统一了应用、桌面图标名称和网页管理界面的 LumiCast 品牌。

- **按国家和地区浏览频道**，可用国家名称或代码搜索分组，按频道名或频道号查找频道。点星标收藏，重启后仍可查看。
- **导入 M3U、M3U8 或 TXT 频道列表**，支持电视遥控器和触屏操作。节目单和直播回看视片源而定。
- **手机竖屏快速换台，横屏全屏观看**。支持截图，Android 5.0 及以上可录制无声 MP4。
- **五种界面语言**支持简体中文、繁體中文、日本語、한국어和 English，可跟随系统或手动切换。

### 下载与安装

- [下载 Android 安装包（APK）](./LumiCast-1.8.5.apk?raw=true)
- [下载 1.8.5 源码（ZIP）](./LumiCast-1.8.5-Source.zip?raw=true)

将 APK 下载到 Android 设备并打开，按系统提示安装。安装包包含 ARM32（`armeabi-v7a`）、ARM64（`arm64-v8a`）和 x86，最低系统要求为 Android 4.0。64 位运行需要 Android 5.0 或更高版本。

### 源码与许可

解压源码 ZIP 后，查看其中的 `README-Multilang.md` 了解构建和签名步骤。常规构建需 JDK 17、Android SDK Platform 34 和 Build Tools 35.0.1。在 `local.properties` 配置 `sdk.dir` 后运行 `./gradlew -PwithoutBrowserCore :app:assembleMultilingualRelease`。

上游 NativeWasmTv 的原创代码采用 GPL-3.0-only，版权声明为 © 2026 buhanzhe and contributors。第三方组件遵循各自的许可证，详情见源码包内的 `LICENSE`、`COPYRIGHT.md` 和 `THIRD_PARTY_NOTICES.md`。

## 日本語

LumiCast は、Android TV、TV ボックス、タブレット、スマートフォン向けのライブ視聴プレーヤーです。[NativeWasmTv](https://github.com/buhanzhe/NativeWasmTv) の標準版をベースに独自にビルドされています。バージョン 1.8.5 では、アプリ名、ホーム画面の表示名、Web 管理画面の名称を LumiCast に統一しました。

- **国・地域ごとにチャンネルを閲覧**でき、国名や国コード、チャンネル名や番号で検索できます。星マークで登録したお気に入りは、アプリの再起動後も保持されます。
- **M3U、M3U8、TXT 形式のチャンネルリストを取り込めます**。テレビのリモコンとタッチ操作に対応しています。番組表と見逃し再生の利用可否は配信元によって異なります。
- **縦画面ではすばやくチャンネルを切り替え、横画面では全画面で視聴**できます。スクリーンショットに対応し、Android 5.0 以上では音声なしの MP4 録画もできます。
- **簡体字中国語、繁体字中国語、日本語、韓国語、英語**に対応しています。端末の言語設定に合わせるか、アプリ内で切り替えられます。

### ダウンロードとインストール

- [Android インストールファイルをダウンロード（APK）](./LumiCast-1.8.5.apk?raw=true)
- [1.8.5 のソースコードをダウンロード（ZIP）](./LumiCast-1.8.5-Source.zip?raw=true)

APK を Android 端末にダウンロードして開き、画面の案内に沿ってインストールしてください。対応アーキテクチャは ARM32（`armeabi-v7a`）、ARM64（`arm64-v8a`）、x86 で、最低動作要件は Android 4.0 です。64 ビットでの実行には Android 5.0 以上が必要です。

### ソースコードとライセンス

ZIP を展開し、`README-Multilang.md` のビルド・署名手順をご覧ください。標準ビルドには JDK 17、Android SDK Platform 34、Build Tools 35.0.1 が必要です。`local.properties` に `sdk.dir` を設定し、`./gradlew -PwithoutBrowserCore :app:assembleMultilingualRelease` を実行します。

NativeWasmTv のオリジナルコードの著作権は © 2026 buhanzhe および貢献者に帰属し、GPL-3.0-only が適用されます。サードパーティ製コンポーネントにはそれぞれのライセンスが適用されます。詳細は ZIP 内の `LICENSE`、`COPYRIGHT.md`、`THIRD_PARTY_NOTICES.md` をご覧ください。

## English

LumiCast is a live streaming player for Android TVs, TV boxes, tablets, and phones. It is an independent build based on the standard edition of [NativeWasmTv](https://github.com/buhanzhe/NativeWasmTv). Version 1.8.5 uses the LumiCast name across the app, its launcher entry, and its web management interface.

- **Browse channels by country or region**, search for groups by country name or code, and find channels by name or number. Starred channels stay in your favorites after you restart the app.
- **Import M3U, M3U8, or TXT channel lists** and navigate with a TV remote or touchscreen. Program guides and catch-up playback depend on the stream provider.
- **Switch channels in portrait mode or watch full-screen in landscape**. You can take screenshots and record silent MP4 clips. Recording requires Android 5.0 or later.
- **Choose from Simplified Chinese, Traditional Chinese, Japanese, Korean, and English** or follow the system language.

### Download and install

- [Download the Android installer (APK)](./LumiCast-1.8.5.apk?raw=true)
- [Download the 1.8.5 source code (ZIP)](./LumiCast-1.8.5-Source.zip?raw=true)

Download the APK to your Android device, open it, and follow the on-screen prompts. The package includes ARM32 (`armeabi-v7a`), ARM64 (`arm64-v8a`), and x86 libraries. The minimum Android version is 4.0. Running in 64-bit mode requires Android 5.0 or later.

### Source and license

Extract the ZIP and see `README-Multilang.md` for build and signing instructions. The standard build uses JDK 17, Android SDK Platform 34, and Build Tools 35.0.1. Set `sdk.dir` in `local.properties`, then run `./gradlew -PwithoutBrowserCore :app:assembleMultilingualRelease`.

Original NativeWasmTv code is copyright © 2026 buhanzhe and contributors and is licensed under GPL-3.0-only. Third-party components retain their respective licenses. See `LICENSE`, `COPYRIGHT.md`, and `THIRD_PARTY_NOTICES.md` in the source archive.
