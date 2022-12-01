# robosys2022
ロボットシステム学の練習リポジトリ

# plusコマンド
![test](https://github.com/yukisato1481/robosys2022/actions/workflows/test.yml/badge.svg)

  * 標準入力から読み込んだ数字の足し算

## インストール方法
  * 下記のコマンドを入力する  
  $ git clone https://github.com/yukisato1481/robosys2022.git  
  * robosys2022が入っていることを確認する  
  $ ls  
  robosys2022  
  * ディレクトリを移動する  
  $ cd robosys2022  
  * インストールが無事完了していることを確認する  
  $ ls  
  LICENSE  README.md  plus  test.bash  

## plus 入出力例
  * 1から5までの数字の足し算
  $ seq 5 | ./plus
  15.0
## 環境
  * Ubuntu 18.04.5 on Windows
  * Python 3.7～3.10

## 動作確認済みの環境
  * Python 3.7～3.10

## ライセンス
  * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
  * © 2022 YUki Sato
