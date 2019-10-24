# Setup

# よく使うコマンド

```

# プロジェクト作成
$ cordova create hello com.example.hello HelloWorld

# CLI のバージョン確認
$ cordova --version

# プラットフォームを追加
$ cordova platform add android    # Android
$ cordova platform add ios        # iOS

# バージョンを指定する場合
$ cordova platform add android@3.7.2

# プラットフォームの確認
$ cordova platform ls

# プラットフォームの削除
$ cordova platform rm android

# アプリをビルド
$ cordova build            # 全部のプラットフォームを
$ cordova build android    # 個別で
$ cordova build --release  # リリースビルド

# cordova build は、以下のコマンドをいっぺんにやってくれている。
$ cordova prepare
$ cordova compile

# ブラウザで動作確認
$ cordova serve android
$ cordova emulate android

# AVD Manager のデバイスを指定する場合
$ cordova emulate --target=Nexus_5_API_22_x86 android

# Android Virtual Device (AVD) Manager のデバイス確認
$ android list avd

# 実機で動作確認
$ cordova run android


# プラグインの確認
$ cordova plugin ls

# プラグインの削除
$ cordova plugin rm org.apache.cordova.geolocation
```
