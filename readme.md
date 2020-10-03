各自のスマホにexpoAppをinstallしておいてください


## 1. dockerコンテナをビルド
``` 
docker-compose build 
```

## 2. コンテナを起動

```
docker-compose up
```

## 3. terminalに表示されている、QRへスマホでアクセス、動作確認。

##　補足
コンテナへ入るには
```
docker-compose run --rm lilas bash --login
```
