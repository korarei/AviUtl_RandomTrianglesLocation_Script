# AviUtl_RandomTrianglesLocation_Script
三角形ポリゴンで構成された面を作成し、そのポリゴンをランダムで表示するAviUtlスクリプト

## はじめに
patch.aulの導入を推奨。
patch.aulで追加される"obj.randex"を利用できる。
[patch.aul謎さうなフォーク版(scrapbox)](https://scrapbox.io/nazosauna/patch.aul)

## 導入・削除
- ### 導入
  1. 同梱の.objファイルをscriptフォルダまたはその子フォルダに入れる。
- ### 削除
  1. 同梱の.objファイルを導入したフォルダから出す。

## 簡単な使い方
画像ループと大体同じ。右下のチェックを入れるとランダム配置、チェックを外すと面を描画する。
詳しくはscrapboxに書いてある。
[ランダム三角ポリ配置(scrapbox)](https://scrapbox.io/korarei/%E3%83%A9%E3%83%B3%E3%83%80%E3%83%A0%E4%B8%89%E8%A7%92%E3%83%9D%E3%83%AA%E9%85%8D%E7%BD%AE)

## LICENSE
LICENSEファイルに記載

## 更新履歴
- v1.0.4
  - 乱数発生処理の改善。
  - エラー処理でpcallを使うように変更。
- v1.0.3
  - patch.aulがない環境でも動作するようにした。
- v1.0.2
  - 縁取り有効時、間隔自動調整機能が上手く動作しない問題を解決。
- v1.0.1 （v1.0.0を使用したPFを読み込むとdialogが全て空白になる。）
  - dialogの変数をローカルからグローバルに変更。（破壊的変更）
  - エラー処理でxpcallを使うようにした。（コンソールだけでなく、フレームバッファにも表示される。）
- v1.0.0
  - リリース