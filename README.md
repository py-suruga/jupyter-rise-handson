# jupyter-rise-handson
Unagi .py / Python駿河 2021/07月のハンズオン資料です

## 使い方

### 必要環境

git, python3.7以上の環境推奨です

```bash
# ディレクトリはお好きなようにしてもらっていいです。以下は一例
cd [作業するディレクトリ]
mkdir pysuruga_jupyter-rise-handson
cd pysuruga_jupyter-rise-handson
git clone https://github.com/py-suruga/jupyter-rise-handson.git 

# 仮想環境作成
python -m venv .venv

# win
.venv/Scripts/activate

# mac, Linux
source .venv/bin/activate

# その先共通
python -m pip install jupyter RISE requests pandas plotly
```

### anaconda向け

※conda環境をあまり利用しないので、詳しくは公式ドキュメントを参照ください

仮想環境作成: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-environments

```bash
# 仮想環境作成
conda create --name pysuruga_jupyter-rise-handson

# 仮想環境有効
conda activate pysuruga_jupyter-rise-handson

# 必要なパッケージのインストール
conda install -c conda-forge rise
conda install -c plotly plotly
```

## ハンズオン内容

- jupyter notebookの基本的な扱い
- RISEを使ってスライドを作ってみる
- みなさんの持ちネタをとりあえず発表してみよう！
- 持ちネタがない人向け: オープンデータでグラフを作りそこからRISEでグラフがあるプレゼンを作ってみます

## あとはipynbファイルを見ながら進めます！