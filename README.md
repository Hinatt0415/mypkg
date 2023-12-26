# mypkg

![test](https://github.com/Hinatt0415/mypkg/actions/workflows/test.yml/badge.svg)

* 本リポジトリはROS2のパッケージである．

# インストール方法
* ROS2未インストールの場合はインストールしてから以下のコマンドでワークスペースにクローン
```
$ git clone https://github.com/Hinatt0415/robosys2023.git   
```

# talker・listener
* ノードを機能させるためにはターミナルが2つ必要
* talkerはcountupというトピックを通して Int16型のメッセージを送信する．
* listenerはcountupからInt16型のメッセージを受信して出力する．


## 著作権・ライセンス
* このソフトウェアパッケージは，[3条項BSDライセンス](https://opensource.org/license/bsd-3-clause/)の下，再頒布および使用が許可されます．
* このパッケージのコードは，上田隆一先生の[スライド](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
* © 2023 Hinata Sakuma
