# Flutter Sandbox

Flutter実験用プロジェクト。

## 環境構築

### FVM

以下のドキュメントに従ってインストールする。

- [https://fvm.app/documentation/getting-started/installation](https://fvm.app/documentation/getting-started/installation)

インストール後、以下のコマンドを実行して、プロジェクトで使用しているバージョンのFlutterをインストールする。

```
fvm use
```

使用しているFlutterのバージョンは `.fvmrc` を参照すること。

### xcodes

以下のドキュメントに従ってインストールする。

- [https://github.com/XcodesOrg/xcodes](https://github.com/XcodesOrg/xcodes)

シミュレータがインストールされていない場合は、Xcode > Window > Devices and Simulatorsを開き、Simulatorsタブの左下の+ボタンを押して適当なデバイスを追加する。

使用しているXcodeのバージョンは `.xcode-version` を参照すること。

### Cocoapods

以下のドキュメントに従ってインストールする。

- [https://guides.cocoapods.org/using/getting-started.html#installation](https://guides.cocoapods.org/using/getting-started.html#installation)

## 実行

以下のコマンドで実行する。

```
fvm flutter run
```
