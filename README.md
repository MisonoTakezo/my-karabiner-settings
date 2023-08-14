# カスタム Karabiner 設定の導入ガイド

このガイドでは、私ののカスタム Karabiner 設定を導入する手順を説明します。Karabiner を使用してキーボードやマウスの動作をカスタマイズすることができます。

## 前提条件

1. macOS 10.12 以降がインストールされていること。
2. Karabiner Elements がインストールされていること。

## インストール手順

1. このリポジトリをクローンするか、ZIP ファイルとしてダウンロードして解凍します。

2. ダウンロードしたフォルダ内に、Karabiner の設定ファイルである `karabiner.json` を配置します。

3. karabiner.jsonは以下のパスに存在します。

   ```shell
   ~/.config/karabiner/
   ```

   karabiner.json を配置したフォルダから設定ファイルをコピーし、置き換えます。

   ```shell
   cp /path/to/downloaded/karabiner.json ~/.config/karabiner/
   ```
