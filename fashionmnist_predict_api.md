# todo
- [x] mnist認識モデルを作成する
- [x] mnist認識モデルを保存する
- [x] 保存したmnist認識モデルをwebapiに読み込ませる
- [x] mnist画像データを生成する
- [x] mnist画像データを投げる
- [x] 画像データを適切な形に変換する
- [x] 予測を行い該当する数字の確率を返す  

``` request command
curl -X POST -F image=@./img/no9.png 'http://localhost:5000/predict'
```