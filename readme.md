各自のスマホにexpoAppをinstallしておいてください


## 1. dockerコンテナをビルド
``` 
docker-compose build 
```

## 2. コンテナへ接続
```
docker-compose run --rm lilas bash --login
```

## 3. expoプロジェクトの作成
```
expo init .
```
blankを選択、hamutarouはtypeScript使いたければ、それ選択。

## 4. コンテナから抜けて、コンテナを起動
```
exit
```

```
docker-compose up
```

5. terminalに表示されている、QRへスマホでアクセス、動作確認。

