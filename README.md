# flutter_web_liff

- 環境
```
% flutter --version
Flutter 3.0.5 • channel stable • https://github.com/flutter/flutter.git
Framework • revision f1875d570e (4 weeks ago) • 2022-07-13 11:24:16 -0700
Engine • revision e85ea0e79c
Tools • Dart 2.17.6 • DevTools 2.12.2
% firebase --version
11.4.2
% npm -v
8.5.5
% node -v
v16.13.2
```

## メモ
- flutterではwebのビルドをするとデフォルトでbuild/webに出力されるので、`firebase.json`の`public`を`build/web`に変更しておく


## command tips

- デプロイ
```
flutter build web
firebase init
```