# プロジェクト名

delete_fence

## 概要

画像内に映る柵を自動で削除します。

## インストール方法

YOLOv5.ipynbまたはYOLOv8.ipynbのコード内で説明されています

また学習済みモデルはgoogle driveからダウンロードしてください

## 検出結果


<img src="https://github.com/miya498/petbottle_detection/assets/100400301/a9ea97b9-86ff-4280-a3b3-55242a16c1f6" width="320px">  <img src="https://github.com/miya498/petbottle_detection/assets/100400301/53353466-9b5e-421f-ae94-631cb63ca0fa" width="320px"> 


## 検出精度

データセットとしてペットボトルが写った画像(267枚)を収集した。これに対してそれぞれの画像を縮小し45,135,225,315度回転させ水増しを行った。
これらをそれぞれ水増しなしのデータセットと水増しありのデータセットとして学習させた。

検出精度としてはYOLOv5xを使い水増しありのデータセットで学習させたモデルが最も優れていた。
