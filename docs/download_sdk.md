# toio SDK for Unity のインストール

## Unity プロジェクト作成

Unity Hub を開き、右上にある【新規作成】をクリック。

<img width=500 src="res/download_sdk/new_project1.png">

プロジェクト作成画面が開かれたら、以下の設定にします。

- テンプレート：3D
- プロジェクト名：なんでも可(ここでは New toio Project)
- 保存先：なんでも可(ここではデスクトップ)

設定が完了したら、【作成】をクリック。

<img width=500 src="res/download_sdk/new_project2.png">

Unity が立ち上がった事を確認しましょう。

## UniTask のインストール

toio SDK for Unity では、Unity に最適化された非同期処理ライブラリ [UniTask](https://github.com/Cysharp/UniTask) を使用しています。<br>
以下のドキュメントを参考に UniTask（2.0.0 以降）をインストールしてください。

* [UniTask の Github リポジトリ](https://github.com/Cysharp/UniTask#install-via-git-url)
* Unity マニュアルの [Git URL からのインストール](https://docs.unity3d.com/ja/current/Manual/upm-ui-giturl.html)

## SDK の追加

### 1. unitypackage のダウンロード
[【コチラ】](https://github.com/morikatron/toio-sdk-for-unity/releases/)から、【toio-SDK-for-Unity.unitypackage】 をダウンロードしてください。

### 2. Unity のプロジェクトにドラッグ&ドロップ
ダウンロードしたフォルダを開いたら、 **【Assets】** フォルダに **【toio-SDK-for-Unity.unitypackage】** をドラック&ドロップします。

<img width=500 src="res/download_sdk/import_sdk.png">

### 3.サンプルの実行、動作確認
Unity プロジェクトに読み込まれたら、`Assets/toio-sdk/Tutorials/1.Basic/0.BasicScene/`までフォルダを移動し、`0.BasicScene シーンファイル`をダブルクリックで開きます。

シーンファイルが開いたら、エディタ上部にあるプレイボタンをクリックします。

<img width=300 src="res/download_sdk/play.png">

 以下のようにサンプルが動く事を確認してください。

<img src="res/download_sdk/sample.gif">

これで toio SDK for Unity のインストールは完了です。