# README

## この Repository の構成

```
+ data
+ tests テスト用データ
	- unittest は、python3標準のunittestを利用している。
	- unittest利用時は、.profileにexport PYTHONPATH=/home/yabuki/src/OpenBadgeV2 などと書いて置くこと
+ Makefile makeコマンドで実行、unittest, clean などが実行できる。使い方は src/OpenBadgeV2 で make とだけ打って helpを出せ
+ BakeBadgeV2.py モジュール。Docstringつけているから見よ。
```

## 追加モジュール

GitHub Actions (以下GHA) で動かすために、ubuntu 20.04 準拠とした。

これらの設定は、手元のpython3.8環境で動かすときに必要です。
GHAで動かす時には、設定済みなので不要です。

```
apt install python3-rfc3986 python3-iso8601
apt install python3-pip
pip3 openbadge_bakery
```

## ライセンス

Apache 2.0 ライセンスです。内容は、LICENSE ファイルを参照してください。

## Authors

著作権が発生するほどのコントリビュートを本プロジェクトに頂いた場合に、お名前と連絡先(Email address)をAuthors.md に記載していきます。

## Thanks

このリポジトリーにあるソフトウェアおよび、GitHub Actions を使った一連のシステムは、LICENCEファイルで定義されたライセンスで公開されます。
この公開に際して、特別な貢献をいただいている方々にたいしての謝辞を Thanks.md に記載いたします。
