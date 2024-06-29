# robot-app
ターミナル上で遊べるアプリ

## Install

1. 以下のようにパーケージをインストールする
```bash
python setup.py develop
```

もしくはroboterフォルダーを実行するディレクトリへ置く

```bash
ls
```
output->roboter


## Requirement
文字を装飾する目的でtermcolorという外部ライブラリを使用しているため、インストールが必要
```bash
pip install termcolor==1.0.0
```

## Usage

ターミナル上で以下を実行
```bash
python main.py
```

### option
- 保存するCSVやテンプレート先を変更する場合は、settings.pyに以下の値を入れる
`vim settings.py`
CSV_FILE_PATH = '/tmp/test.csv'
TEMPLATE_PATH = '/tmp/templates/'

- `settings.py`ファイルを作成した場合は、変更しない場合のDefaultを以下のように設定する
CSV_FILE_PATH = None
TEMPLATE_PATH = None
