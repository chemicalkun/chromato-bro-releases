# Chromato BRO

GPC/SECデータ解析ソフトウェア。Mac（Apple Silicon）・Windows 11（Intel/AMD）に対応します。

## ダウンロード

[最新版のダウンロード](https://github.com/chemicalkun/chromato-bro-releases/releases/latest)

- Mac：Mac版ZIPを展開し、Chromato BRO.appをアプリケーションフォルダへ移動します。
- Windows：Windows版ZIPを展開し、Chromato BRO Windowsフォルダ内のChromato BRO.exeを実行します。フォルダ内のDLL等も必要です。.NET Runtimeは同梱しています。WebView2 Runtimeが必要です。
- 測定データは外部に送信せず、解析は端末内で実行します。

## アプリ内アップデート

Macの「Chromato BRO」、Windowsの「ヘルプ」メニューから「アップデート設定…」を開き、次のURLを保存します。

`https://github.com/chemicalkun/chromato-bro-releases/releases/latest/download/updates.json`

「アップデートを確認…」から更新できます。更新機能のない旧版には、まず最新版ZIPを導入してください。通常の解析中には更新通信を行いません。

## 配布について

このリポジトリはアプリの配布専用です。開発プロジェクト・利用者の測定ファイル・署名用秘密鍵は掲載しません。Chromato-PROおよびメーカーの公式製品ではありません。

Mac版はDeveloper ID署名・Apple公証なし、Windows版はAuthenticode未署名です。起動時にOSの確認が表示される場合があります。Windows実機での動作確認は未実施です。
