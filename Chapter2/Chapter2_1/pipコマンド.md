# 2.1.3pipコマンド

pip<br>
* Pythonで使えるサードパーティー製パッケージをインストールするためのツール
* サードパーティー製パッケージはPyPIというサイトで公開されている
* pip install ~~ とすることで、PyPIのパッケージをインストール出来る

インストール<br>
* $ pip install numpy

アンインストール<br>
* $ pip uninstall numpy

特定のバージョンでインストール<br>
* $ pip install numpy==1.14.1

インストール済みのパッケージを更新<br>
* $ pip install -U numpy

pip自体を更新<br>
* $ pip install -U pip

インストール済みのパッケージ一覧を表示<br>
* $ pip list

アップデート可能なパッケージの一覧を表示<br>
* $ pip list -o

現在インストール済みのパッケージとそのバージョンをファイルに出力<br>
* $ pip freeze > requirements.txt

ファイルを元に必要なパッケージのインストール<br>
* $ pip install -r quirements.txt