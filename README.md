### ros_test
パブリッシャでカウントアップした値をサブスクライバで累乗するROSのパッケージです。

### 使い方
1. roscore でROSの基盤となるプログラムを立ち上げる
2. rosrun ros_test count.py でパブリッシャのノードを立ち上げる
3. rosrun ros_test power.py でサブスクライバのノードを立ち上げる
4. rostopic echo /count_up でカウントアップした値を表示する
5. rostopic echo /power で で累乗した値を表示する

### デモ
https://www.youtube.com/watch?v=HpR9kfZO8aA&feature=youtu.be

### 動作環境
RaspberryPi3B+  
Ubuntu 18.04 server   
ROS Melodic Morenia  

### ライセンス
GPL
