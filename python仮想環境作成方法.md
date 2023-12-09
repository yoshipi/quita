---
title: newArticle001
tags:
  - ''
private: false
updated_at: ''
id: null
organization_url_name: null
slide: false
ignorePublish: false
---
# Pythonの仮想環境作成方法
## 仮想環境を作成する目的
複数のバージョンのPythonを使用する場合には、仮想環境を作成する。

## 仮想環境作成
venvの後ろにディレクトリパスを指定すると、仮想環境の作成ができる。

~~~
python -m venv 
~~~

`--upgrade-deps`をつけて実行すると、仮想環境専用のpipが最新版に更新される。

## 仮想環境の有効化
pathの部分は、仮想環境を作成したディレクトリパス

~~~
{path}\Scripts\activate.bat
~~~

## 仮想環境の無効化

~~~
deactivate
~~~

## pipの最新化コマンド

~~~
pip install --upgrade pip
~~~