# RecipePack 仕様

## 概要
RecipeChainAnalyzer が扱う RecipePack のフォーマット仕様を定義する。

## フォーマット
JSON形式。基本構造は [samples/simple.json](./samples/simple.json) を参照。

## フィールド定義

| フィールド | 型 | 説明 |
|---|---|---|
| name | string | パック名 |
| version | string | バージョン |
| recipes | array | レシピ一覧 |

## バリデーションルール

## バージョニング方針
