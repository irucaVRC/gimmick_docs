# 拡張メニューv2 概要
本アセットをワールドに設置することでVRChatのメニューと連動する拡張メニューが使えるようになります。

PC, Android, iOSに対応。
デスクトップ, VR, スマホどの環境からも利用できます。

Unity 2022.3.22f1で動作確認済みです。

旧バージョンの拡張メニューとは互換性がありません。ご注意ください。

:::note 注意
本アセットは容量削減のため、フォントアセットに空フォントを使用しています。
これはUnityエディタ上では日本語の文字が豆腐(□)になってしまいますが、VRChat上ではVRChat内部のフォント(日本語の場合はNoto Sans JP)にフォールバックされて正しく表示されます。

Unityエディタ上でも正しく表示され、かつワールド容量を増やさないようにする場合は、以下の設定を行ってください。
1. Edit→Project Settingsを開く
2. Text Mesh Proを展開し、Settingsを開く
3. Fallback Font Assets Listに、日本語に対応したFont Assetを入れる

※Font Assetの作成方法は、[こちらのサイト](https://zenn.dev/kametani256/articles/63c083ab318136)等を参照してください。
:::