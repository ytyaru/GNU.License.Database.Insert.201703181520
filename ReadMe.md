# このソフトウェアについて

GNUサイトからライセンス情報を抽出してDBに挿入する

# 開発環境

* Linux Mint 17.3 MATE 32bit
* [SQLite3](https://www.sqlite.org/index.html) 3.8.2

# 元データ

https://www.gnu.org/licenses/license-list.ja.html

# 準備

* [データベースを作成する](https://github.com/ytyaru/GNU.License.Database.Create.201703180758)

# 実行

```sh
python3 main.py
```

# 結果

* `GNU.Licenses.sqlite3`ファイルにデータが挿入される

# ライセンス #

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

なお、使用させていただいたソフトウェアは以下のライセンスである。感謝。

Library|License|Copyright
-------|-------|---------
https://www.gnu.org/licenses/license-list.ja.html|[CC-BY-ND-4.0](https://creativecommons.org/licenses/by-nd/4.0/deed.ja)|Copyright © 2014, 2015, 2016 Free Software Foundation, Inc.

改変禁止のため、作成したDBファイルは配布できない。

