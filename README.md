# ros2_ws

[![test](https://github.com/keigo0918/ros2_ws/actions/workflows/test.yml/badge.svg)](https://github.com/keigo0918/ros2_ws/actions/workflows/test.yml)

このリポジトリは千葉工業大学先進工学部未来ロボティクス学科2023年度ロボットシステム学の講義にて作成したリポジトリである。

## 各ノードの説明
* talker
  * naosv
* listener
* launch

## ダウンロード

```
$ git clone https://github.com/keigo0918/ros2_ws.git
```

```
$ cd ros2_ws
```

## 実行結果

* talkerの実行結果
単体で動作させる際は、下記のコマンドを打ち込むことで実行可能。
```
$ ros2 run mypkg talker
#画面には何も表示されません
```
Ctrl+Cで終了。

* listenerの実行結果
単体で動作させる際は、下記のコマンドを打ち込むことで実行可能。
```
$ ros2 run mypkg listener
[INFO] [1703316207.377518470] [listener]: Listen: 0
[INFO] [1703316207.869697454] [listener]: Listen: 1
[INFO] [1703316208.376130983] [listener]: Listen: 2
・・・
```
Ctrl+Cで終了。

* launchの実行結果
```
$ ros2 launch mypkg talk_listen.launch.py 
[listener-2] [INFO] [1703318314.068463454] [listener]: Listen: 0
[listener-2] [INFO] [1703318314.568180831] [listener]: Listen: 1
[listener-2] [INFO] [1703318315.068308484] [listener]: Listen: 2
・・・
```
Ctrl+Cで終了。

## テスト環境

* Ubuntu 20.04
* ROS2 foxy

## ライセンス

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを本人の許可を得て自身の著作として改変したものです.
  * [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

* © 2023 Keigo Shishido  
