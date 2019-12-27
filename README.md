# 2019ロボットシステム学課題１
# 概要
　入力した数字の回数点灯し(3まで)，0を入力すると消灯するデバイスドライバ．
# 手法
## インストール手順
```
$ git clone https://github.com/KosekiTakashi/myled.git
$ cd myled
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
## 実行
```
$ echo 0 > /dev/myled0
$ echo 1 > /dev/myled0
$ echo 2 > /dev/myled0
$ echo 3 > /dev/myled0
```
## youtube
　https://youtu.be/OfBfnKCStB0
