# plotly_demo

## 概要

plotlyのデモをする為の環境構築の説明です。

## セキュリティグループグループの作成

- 22,80,8888ポートを許可設定にする。
- EC2にセキュリティグループを適応する。

## AWS EC2のJupyter labを実行する為のコマンド

```bash
# jupyterlabインストール
pip3 install jupyterlab
# gitのインストール
sudo yum install git -y
# githubからソースをクローン
git clone https://github.com/YukiTsukisaka/plotly_demo.git
# jupyterlabの起動
jupyter-lab --ip='0.0.0.0'
```

## Jupyter labにアクセス

コンソール上に表示されるIPアドレスとトークンを元にアクセス
<http://xxx.xxx.xxx.xxx:8888/lab?token=user_token>  
※初回だけWeb画面でトークンの入力を求められるので入力
