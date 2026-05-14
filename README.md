# factory-tool

第2工場の Excel データから機械情報を抽出するツールです。

## 概要
Excelファイルから「第2工場」のデータを抽出し、
必要な項目だけを整理して出力します。

## 必要環境
- Python 3.x
- openpyxl

## インストール
以下を実行してください：

pip install openpyxl

## 使い方
1. Excelファイルを準備
2. スクリプトを実行

python factory2_extract.py

## ファイル構成
- factory2_extract.py : 抽出処理メイン

## 注意
- Excelに「OrderNo」列が存在する必要があります
- 特定フォーマット前提です

## 作者
ugu00x-cell
