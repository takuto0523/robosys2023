# robosys2023

# plus コマンド
[![test](https://github.com/takuto0523/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/takuto0523/robosys2023/actions/workflows/test.yml)


標準入力から読み込んだ数字を足すソフトです。

実行のやり方は,
```
$ seq 5 | ./plus
```
seqの後の数字は5でなくても大丈夫です。

実行結果は、
```
15
```
と出力されます。

## 必要なソフトウェア
* Python
  * テスト済み: 3.7～3.10

## テスト環境
* Ubuntu 22.04.2 LTS

## 著作権・ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは、下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda) のものを、本人の許可を得て自身の著作としたものです。一部コードを改変しました。
  * [ryuichiueda/my_slides/robosys2022/lesson3.md](https://github.com/ryuichiueda/my_slides/blob/e62cce75befe2433a96c1e813bcc0eaa2941305b/robosys_2022/lesson3.md)
* © 2023 Takuto Suzukawa

## インストール方法
* GitHubが利用できる環境で下記のコマンドを入力してください。

```
$ git clone https://github.com/takuto0523/robosys2023.git
```
