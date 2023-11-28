# Docker-com

## 学習環境
* Ubuntuを使用

* 実行中のコンテナをリストで表示
```
docker ps          <!-- Dockerで実行中のコンテナを表示 -->
```

* 全てのコンテナをリストで表示
* psコマンドのaオプション（allオプション）を使用
* デフォルトでは実行中のものだけを表示することに注意
```
docker ps -a         <!-- Dockerでコンテナを全て表示 -->
docker ps --all
```

* 実行中のコンテナを停止
```
docker stop          <!-- Dockerで実行中のコンテナを停止 -->
```
