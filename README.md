# 汎用用語の調査メモ

特定の製品に依存しなさそうなものの調査結果をメモする箇所

## ルール

* 技術要素ごとにディレクトリを作成し、Markdown形式のファイルにメモを記載する  
例：DB関連の技術のメモは「DB」ディレクトリに格納する
* メモの文字コードはUTF-8
* Markdownファイルの記載内容は後述の内容を満たすこと

### 記載内容

最低限、以下の構成を守る  
参考サイトは、最後にまとめて書くようにするが、状況に応じて、本文の中に記載する
```
# <タイトル>

## 概要

数行の概要


>>>
以下、固有の内容を書いていく

・見出しは「##」以下で書く
>>>
---

### 参考
* 参考サイト1  
* 参考サイト...
* 参考サイトN
```