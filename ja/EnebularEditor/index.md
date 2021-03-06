---
lastUpdated: 2018-11-29
---

# enebular editor {#enebular editor}

## Overview {#Overview}

enebular editor は ブラウザ上ではなくローカル環境でフローの編集とデプロイ（ `AWS IoT`, `Pelion Device Management`, `AWS Lambda`, `Heroku`）のできるソフトウェアです。

## Modes {#Modes}

enebular editor には `Desktop` と `Remote` の二つのモードがあります。

### Desktop {#Desktop}

デスクトップモードは、ノード のサポートが PC やブラウザの API に限られている場合に使用します。
enebular editor はクラウドではなくアプリケーションからフローエディタを読み込みます。

デスクトップモードはポート`1888`で走っています。

### Remote {#Remote}

[enebular-runtime-agent v2.3.0](https://github.com/enebular/enebular-runtime-agent/releases) 以降\*\* の linux デバイス（Raspberry Pi など）のフローを編集する場合に使用します。
Raspberry Pi のセンサー用ノードなど、デバイスでしか動かないノードを用いたフローを編集することができます。
AWS IoT または Pelion Device Management との接続が必要です。（Pelion Device Management の場合 [enebular-runtime-agent-cloud-connector 2.3.0](https://github.com/enebular/enebular-runtime-agent-mbed-cloud-connector/releases) を使用してください。）
enebular editor は `enebular-runtime-agent` のフローエディタをリモートで開きます。

## Requirements {#Requirements}

- enebular アカウント
- ネットワークに接続している PC
- [Node 10.14.2 LTS](https://nodejs.org/ja/)

## How to install {#How to install}

### For Windows {#For Windows}

1. [こちら](https://s3-ap-northeast-1.amazonaws.com/enebular-editor/win/enebular+editor+Setup+0.9.0.exe)からインストーラをダウンロードします。

1. exe ファイルのインストーラーを実行します。

### For Mac {#For Mac}

1. [installer](https://s3-ap-northeast-1.amazonaws.com/enebular-editor/mac/enebular+editor-0.9.0.dmg)からインストーラをダウンロードします。

1. dmg ファイルのインストーラーを実行します。

1. **enebular editor** を実行します。
