# Groonga Quick-Start

___

## この資料へのリンク

http://redfigure.github.io/slide/groonga_quickstart/

---

## インストールがめんどくさい人！

[Try-Groonga](http://try-groonga.herokuapp.com/)

try-groonga でググると出てきます

___

## Windowsの人

インストーラーからインストールが可能です。

[公式ドキュメント](http://groonga.org/ja/docs/install/windows.html)を参照してください。

___

## CentOSの人！

```
% sudo yum install -y groonga-tokenizer-mecab
% sudo rpm -ivh http://packages.groonga.org/centos/groonga-release-1.1.0-1.noarch.rpm
% sudo yum makecache
% sudo yum install -y groonga
```

___

## Debianの人！

```
% sudo vi /etc/apt/sources.list.d/groonga.list:
deb http://packages.groonga.org/debian/ wheezy main
deb-src http://packages.groonga.org/debian/ wheezy main

% sudo apt-get install -y -V groonga-tokenizer-mecab

% sudo apt-get update
% sudo apt-get install -y --allow-unauthenticated groonga-keyring
% sudo apt-get update
% sudo apt-get install -y -V groonga
```

___

## Ubuntuの人！

```
% sudo apt-get -y install groonga-tokenizer-mecab
% sudo apt-get -y install software-properties-common
% sudo add-apt-repository -y universe
% sudo add-apt-repository -y ppa:groonga/ppa
% sudo apt-get update
% sudo apt-get -y install groonga
```

___

## OSX の人！

MacPortsかHomebrewで手順が異なります。

[公式ドキュメント](http://groonga.org/ja/docs/install/mac_os_x.html)を参照してください。

___

## それ以外のLinuxの人！

- [Fedoraの場合](http://groonga.org/ja/docs/install/fedora.html)
- [Solarisの場合](http://groonga.org/ja/docs/install/solaris.html)
- [公式ドキュメントのインデックス](http://groonga.org/ja/docs/)

---

# インストール後

groongaコマンドが使えるか確認してください。

```
% groonga
>
```

---

# Groonga Practice

チュートリアルDDLの簡単セットアップツール。

※ try-groongaでは使えません

[hiroyuki-sato/groonga_practice](https://github.com/hiroyuki-sato/groonga_practice)

---

# Let's Groonga.

