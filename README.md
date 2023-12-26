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

## 実行例
例では端末1をtalker側，端末2をlistener側として実行する．

* 端末1 (入力)
```
$ ros2 run mypkg talker
```

* 端末2 (入力)
```
$ rou2 run mypkg listener
```

* 端末2 (出力)
```
[INFO] [1703611792.008532177] [listener]: Listen: 0
[INFO] [1703611792.498053502] [listener]: Listen: 1
[INFO] [1703611792.998608227] [listener]: Listen: 2
[INFO] [1703611793.499302467] [listener]: Listen: 3
[INFO] [1703611793.998724231] [listener]: Listen: 4
[INFO] [1703611794.497946359] [listener]: Listen: 5
[INFO] [1703611794.997757105] [listener]: Listen: 6
[INFO] [1703611795.497934088] [listener]: Listen: 7
[INFO] [1703611795.997992620] [listener]: Listen: 8
[INFO] [1703611796.498351098] [listener]: Listen: 9
[INFO] [1703611796.997554596] [listener]: Listen: 10
```

## 著作権・ライセンス
* このソフトウェアパッケージは，[3条項BSDライセンス](https://opensource.org/license/bsd-3-clause/)の下，再頒布および使用が許可されます．
* このパッケージのコードは，上田隆一先生の[スライド](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
* © 2023 Hinata Sakuma
