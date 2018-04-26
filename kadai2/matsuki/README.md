# conv_img

[![CircleCI](https://circleci.com/gh/matsu0228/go_sandbox.svg?style=svg)](https://circleci.com/gh/matsu0228/go_sandbox)

* sample command
  * 下記で、画像変換ができるコマンド
```
conv_img -d *your_dir* ( -f *from_format:dest_format* )
```
* option
  * d: 必須。指定したディレクトリ配下を再帰的に処理する
  * f: デフォルト=jpg:png。変換前の形式と変換後の形式を指定できる


# test

* following
```
$ go test -cover ./convimg
ok  _/home/dev/go-tutorial/dojo1/kadai2/matsuki/convimg4.069scoverage: 86.6% of statements
```