# AuraPrism 体験版ダウンロード / Trial downloads

AuraPrism は各社カメラの RAW に対応した Windows 用の RAW 現像ソフトです。
このリポジトリは体験版インストーラーの配布専用で、ソースコードは含みません。

AuraPrism is a RAW photo developer for Windows that supports most camera makers.
This repository only hosts the trial installer. It contains no source code.

## ダウンロード / Download

**最新版 / Latest:** [AuraPrism-setup.exe](https://github.com/fujino6x28/AuraPrism-releases/releases/latest/download/AuraPrism-setup.exe)

過去の版は [Releases](https://github.com/fujino6x28/AuraPrism-releases/releases) にあります。
Older versions are on the [Releases](https://github.com/fujino6x28/AuraPrism-releases/releases) page.

- 動作環境 / Requirements: Windows 10 / 11 (64-bit)
- 体験版は期限なしで使えます。書き出し画像に透かしが入り、一部の機能が使えません。
  The trial never expires. Exported images carry a watermark and some features are locked.
- 製品版のご購入、機能の詳細、お問い合わせは公式サイトへ。
  For purchase, features and support, see the official site: https://auraprism.pages.dev

## インストール時の警告について / About the Windows warning

「Windows によって PC が保護されました」と表示された場合は、「詳細情報」→「実行」で進めてください。
If Windows shows "Windows protected your PC", click "More info" and then "Run anyway".

---

## 新しい版を公開する手順(管理者向けメモ)

1. `build.bat` で `dist\AuraPrism-<版>-setup.exe` を作る
2. ファイル名を **`AuraPrism-setup.exe`** に変える(上の「最新版」リンクとサイトのボタンがこの名前を指すため)
3. このリポジトリの Releases →「Draft a new release」で、タグに `v<版>`(例 `v1.0.0`)を付け、exe を添付して公開
