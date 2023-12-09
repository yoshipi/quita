---
title:Pythonの仮想環境作成方法
tags:
  -Python
  -初心者
private: false
updated_at: '2023-12-09T18:12:30+09:00'
id: 9d2d1b8bfc179978cf34
organization_url_name: null
slide: false
ignorePublish: false
---



## 仮想環境を作成する目的

複数のバージョンのPythonを使用する場合には、仮想環境を作成する。

## 仮想環境作成

venvの後ろにディレクトリパスを指定すると、仮想環境の作成ができる。

~~~bash
python -m venv 
~~~

`--upgrade-deps`をつけて実行すると、仮想環境専用のpipが最新版に更新される。

## 仮想環境の有効化

pathの部分は、仮想環境を作成したディレクトリパス

~~~bash
{path}\Scripts\activate.bat
~~~

## 仮想環境の無効化

~~~bash
deactivate
~~~

## pipの最新化コマンド

~~~bash
pip install --upgrade pip
~~~
