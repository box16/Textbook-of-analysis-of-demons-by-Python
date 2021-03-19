# 2.2.1Python文法

Pythonの文法の設計思想<br>
* シンプルで読みやすいコードが書けること

インデント<br>
* Pythonはコードのブロック構造をインデントで表現する
* [sample.py](https://scrapbox.io/api/code/InoueStudying/2.2.1Python%E6%96%87%E6%B3%95/sample.py)
* for i in range(0,10):
* print(i)
* ブロックは1つのtab(4つのスペース)で区切られる

コーディング規約<br>
* Pythonの標準のコーディング規約はPEP8(ペップエイト)と呼ばれている
* [https://www.python.org/dev/peps/pep-0008/](https://www.python.org/dev/peps/pep-0008/)
* PythonプログラマーはこのPEP8に準拠したコーディングを心がける

pycodestyle<br>
* pycodestyleというツールを用いれば、作成したPythonファイルがPEP8に違反していないかをチェックできる
* $ pip install pycodestyle
* $ pycodestyle ~~.py

Flake8<br>
* 定義したが使用していない変数、importしたが使用していないモジュールが無いかをチェックするツール
* $ pip install flake8
* $ flake8 ~~.py

