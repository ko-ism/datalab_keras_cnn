# GCP
Datalab上で、Keras/TensorFlowを利用して、画像分類をしています。（CNN、畳み込みニューラルネットワーク）

## 準備
* バケットにラベルと同じ名前のフォルダで学習用画像を用意
* 作ったモデルを指定のバケットへ保存


```
#nakamotoとjiroの2ラベルなら、以下のようなフォルダ構造
bucket
      -- nakamoto/
      -- jiro/
```
