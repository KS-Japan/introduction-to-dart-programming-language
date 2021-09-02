# introduction-to-dart-programming-language
The Dart Programming Language 

### Flutter アップデート方法
安定版に切り替え<br>
```
flutter channel stable
```
アップデート
```
flutter upgrade
```

### Flutter 外部パッケージを利用
外部ライブラリを利用するときは`pubspec.yaml`のdependenciesに記載をする<br>
例：<br>
```
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  english_words: ^4.0.0   
```
ターミナルで`flutter packages get`と実行するとpubspec.lock ファイルに自動生成されます<br>
このファイルには、プロジェクトに取り込まれたすべてのパッケージとそのバージョン番号のリストが含まれます<br>
