# java_hub
簡易的な `java_home` を目指し作成。

リストは手動で更新するため様々なインストール方法でインストールした java をまとめて記述することが可能。

## 使い方
1. `bin/java_hub` をパスに通す
2. ホームディレクトリ以下にバージョンとファイルパスを空白区切りで入力した `.java_hub.dat` を作成する
3. 取得したいバージョン名をオプションとしてコマンドを実行 `java_home -v 13`

.java_hub.dat 例
```
8 /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/bin/java
13 /usr/bin
```
