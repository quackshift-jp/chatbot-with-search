# LangChainを使った、社内ドキュメント検索アプリケーション

## 使用デモ
使用動画を貼り付けたい.

## 使用技術
Python 3.9.12
Pythonライブラリ（バージョンはrequirements.txtに記載）
フレームワークはStreamlit[https://streamlit.io/]を採用

## 開発用ドキュメント
### Step1: git cloneにて、リポジトリをローカル環境に複製する & 作業ブランチを切る
```
$ git clone https://github.com/quackshift-jp/quackshift-search-with-langchain.git
$ cd path/to/quackshift-search-with-langchain && git switch main
$ git pull
$ git checkout -b feature/hogehoge_YYYYMMDD
```

### Step2: Python仮想環境のアクティベート
```
$ python3 -m venv .venv && source .venv/bin/activate
$ pip install -r requirements.txt
```
