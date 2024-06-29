# robot-app
ターミナル上で遊べるアプリ
====

## Install

1. 以下のようにパーケージをインストールするか、もしくはroboterフォルダーを実行するディレクトリへ置く
```bash
python setup.py develop
```

or

```bash
ls
```
roboter


## Requirement
```bash
pip install termcolor==1.0.0
```

## Usage

ターミナル上で以下を実行
```bash
python main.py
```

(オプション: 保存するCSVやテンプレート先を変更する場合は、settings.pyに以下の値を入れる)
# vim settings.py
CSV_FILE_PATH = '/tmp/test.csv'
TEMPLATE_PATH = '/tmp/templates/'

# settings.pyファイルを作成した場合は、変更しない場合のDefaultは以下に設定する
CSV_FILE_PATH = None
TEMPLATE_PATH = None
