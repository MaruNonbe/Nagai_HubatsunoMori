# 長井市 不伐の森ARガイド WebAR 修正版

## 公開時に使うフォルダー
01_WebAR の中身を、公開用フォルダーの root に置いてください。

公開用root/
├─ index.html
└─ assets/
   ├─ models/
   │  └─ unfelled_forest_character.glb
   ├─ audio/
   ├─ images/
   └─ markers/

## スマホでの確認
- iPhone: Safari
- Android: Chrome
- HTTPS環境が必要です。

## 音声ファイル
音声ガイドを使う場合は、以下のファイル名で assets/audio/ に入れてください。

- unfelled_forest_ja.wav
- unfelled_forest_en.wav
- unfelled_forest_zh.wav
- unfelled_forest_ko.wav

音声ファイルがない場合でも、AR表示と字幕表示は動きます。
ブラウザが対応している端末では、未配置の言語音声は端末の音声合成にフォールバックします。
