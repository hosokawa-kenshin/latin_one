<p align="center">
<img src="./assets/images/linkedin_banner_image_2.png" alt="TUI">
コーヒー豆注文アプリケーション ☕️☕️☕️
</p>
<p align="center">
<img src="https://img.shields.io/badge/Flutter-blue?color=45b8cd&logo=flutter&style=flat-square">
<img src="https://img.shields.io/badge/-Firebase-ef5350.svg?logo=firebase&style=flat-square">
<a href="https://github.com/hosokawa-kenshin/Gcal.js/blob/main/README-ja.md">
    <img height="20px" src="https://img.shields.io/badge/JA-flag.svg?color=45b8cd&style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj4NCjxwYXRoIGZpbGw9IiNmZmYiIGQ9Im0wLDBoOTAwdjYwMGgtOTAweiIvPg0KPGNpcmNsZSBmaWxsPSIjYmUwMDI2IiBjeD0iNDUwIiBjeT0iMzAwIiByPSIxODAiLz4NCjwvc3ZnPg0K">
  </a>
<img alt="GitHub License" src="https://img.shields.io/github/license/hosokawa-kenshin/latin_one?style=flat-square&logoColor=45b8cd&color=45b8cd">
<br>
</p>

<p>
<p align="center">
<a href="https://github.com/hosokawa-kenshin/Gcal.js" target="__blank"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/hosokawa-kenshin/latin_one?logoColor=black"></a>
</p>

<p align="center">
<img src="./assets/images/latinone_home.png" alt="LatinOne Home" width="200">
<img src="./assets/images/latinone_storeselect.png" alt="LatinOne Home" width="200">
<img src="./assets/images/latinone_product_summary.png" alt="LatinOne Home" width="200">
</p>

## LatinOne
本リポジトリは，2024年度乃村研究室勉強会の題材として開発したコーヒー豆注文アプリのリポジトリである．

## SDK Version
```bash
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel stable, 3.24.5, on macOS 12.6 21G115 darwin-arm64, locale ja-JP)
[✓] Android toolchain - develop for Android devices (Android SDK version 34.0.0)
[✓] Xcode - develop for iOS and macOS (Xcode 14.2)
[✓] Chrome - develop for the web
[✓] Android Studio (version 2023.2)
[✓] VS Code (version 1.96.2)
[✓] Connected device (3 available)
```

## Setup
1. 本プロジェクト を clone する
```bash
git clone git@github.com:hosokawa-kenshin/latin_one.git
```
2. 依存関係をインストールする
```bash
cd latin_one
flutter pub get
```
3. アプリを実行する
```bash
flutter run
```

## 関連リポジトリ
### バックエンドアプリケーション
- [latin_one_server](https://github.com/fujiwara-e/latin_one_server) - バックエンドサーバアプリケーション

### コンソールアプリケーション
- [latin_one_client](https://github.com/fujiwara-e/latin_one_client) - コンソール管理アプリケーション

## Features
- データベース (Firebase Firestore)
- プッシュ通知 (Firebase Cloud Messaging)
- コーヒー豆の注文

## License
このプロジェクトはBSD 3-Clause Licenseの下でライセンスされている．
詳細については，[LICENSE](LICENSE)ファイルを参照．
