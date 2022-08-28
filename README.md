# java_hub
java のバージョン指定をファイルで記述して利用する

## 使い方
1. `bin/java_home` をパスに通す
2. ホームディレクトリ以下にバージョンとファイルパスを空白区切りで入力した `.java_hub.dat` を作成する
3. 取得したいバージョン名をオプションとしてコマンドを実行 `java_home -v [バージョン名]`

.java_hub.dat 例
```
8 /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home/bin/java
13 /usr/bin
```
