# 1から学ぶLinux入門ハンズオン

## Chapter.0 事前準備

### Windowsの方

1. Cygwinをインストールしてください。

   [Cygwinダウンロードサイト](https://cygwin.com/install.html)

2. Java 8をインストールしてください。

    [Java 8ダウンロードサイト](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

3. Cygwin上で以下のコマンドを入力して表示されるバージョンが`1.8.X_XX`になっていることを確認してください。

```
$ java -version
```

### Macの方

1. Java 8をインストールしてください。

    [Java 8ダウンロードサイト](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

2. ターミナルを開き、以下のコマンドを入力して表示されるバージョンが`1.8.X_XX`になっていることを確認してください。

```
$ java -version
```

3. 下記のコマンドを入力しHomebrewをインストールしてください。

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

4. 下記のコマンドを入力しwgetコマンドをインストールしてください。

```
$ brew install wget
```

5. 下記のコマンドを入力してwgetのバージョンが表示されたらインストール成功です。

```
$ wget -V
```

