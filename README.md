# Shell-study

## 学習環境
* Ubuntuを使用

## コマンドリスト （ディレクトリ・ファイル操作）
* ディレクトリにおける現在位置の確認
```
pwd
```

* ディレクトリ内のファイル全表示
```
ls
```

* ディレクトリ階層の移動
```
cd sampledir                                      <!-- 参照階層内の対象ディレクトリに降りる -->
cd ../                                            <!-- 参照階層からひとつ上のディレクトリに上がる -->
```

* ディレクトリの作成
```
mkdir sampledir                                   <!-- 参照階層内にsampledirディレクトリを作成する -->
```

* ファイルの作成
```
touch samplet.txt                                  <!-- 参照階層内にテキストファイルsampletを作成する -->
touch samplej.java                                 <!-- 参照階層内にJavaファイルsamplejを作成する -->
```

* ファイルの移動
* ファイル名の変更も行うことができる
```
mv samplet.txt sampledir                           <!-- samplet.txtをsampledirディレクトリに移動する -->
mv samplet.txt samplexx.txt                        <!-- ファイル名をsampletからsamplexxに変更する -->
```

* ファイルのコピー
```
cp samplet.txt sampledir                           <!-- samplet.txtをsampledirディレクトリにコピーする -->
```

* ファイルの削除
```
  rm samplet.txt                                   <!-- samplet.txtを削除する -->
```

* テキストファイルへの書き込み
```
  nano samplet.txt                                 <!-- samplet.txtへの書き込み画面を表示 -->
```

* テキストファイルの内容確認
```
  cat samplet.txt                                   <!-- samplet.txtの内容を表示する -->
```

## コマンドリスト （PC）
* 現在のディスク使用量の確認
```
du
```
* 現在のディスクの空領域の確認
```
df
```
* 現在のメモリ使用状況の確認
```
free
```
* 現在実行中のプロセスを一覧表示
```
ps
```


