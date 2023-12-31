# Perm-study

## 学習環境
* Ubuntuを使用

## パーミッションとは
* Linuxにおけるアクセス権限のこと
* 設定対象はファイルやディレクトリ
* 権限は「ユーザー／所属グループ／グループ外」の各段階に設定される
* 権限は「r=read 読み取り」、「w=write 書き込み」、「x=exec 実行可能」の３種がある
* 権限が無いアクセスはエラーになる

## コマンド
* パーミッションの状態確認
* lsコマンドのlaオプションを使用
```
ls -la
```

* 権限の変更
* 許可する権限を「r=4」、「w=2」、「x=1」の合計値にして段階順に並べる。
```
chmod 755 sample.txt         <!-- sample.txtの権限変更　ユーザー/グループ/グループ外 --> 
```

* 権限所有者の変更
```
chown tester sample.txt          <!-- sample.txtの所有者をtester(ユーザ)に変更 -->
chown tester:user sample.txt     <!-- sample.txtの所有者をtester(ユーザ)とuser(グループ)に変更 -->
```

* より強い権限によるコマンドの実行
```
sudo chmod 755 sample.txt    <!-- より強い権限からのchmodコマンド実行 -->  
```
