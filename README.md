# Shell-study

## 学習環境
* Ubuntuを使用

## コマンドリスト 
* ディレクトリにおける現在位置確認
```
pwd
```

* ディレクトリ内のファイル全表示
```
ls
```

* ディレクトリ階層の移動
```
cd sampledir                                                            <!-- 参照階層内の対象ディレクトリに降りる -->
cd ../                                                                  <!-- 参照階層からひとつ上のディレクトリに上がる -->
```

* ディレクトリの作成
```
mkdir sampledir                                                          <!-- 参照階層内にsampledirディレクトリを作成する -->
```

* ファイルの作成
```
touch samplet.txt                                                        <!-- 参照階層内にテキストファイルsampletを作成する -->
touch samplej.java                                                       <!-- 参照階層内にJavaファイルsamplejを作成する -->
```

* ファイルの移動
* ファイル名の変更も行うことができる
```
mv samplet.txt sampledir                                                  <!-- samplet.txtをsampledirディレクトリに移動する -->
mv samplet.txt samplexx.txt                                               <!-- ファイル名をsampletからsamplexxに変更する -->
```

* ファイルのコピー
```
cp samplet.txt sampledir                                                  <!-- samplet.txtをsampledirディレクトリにコピーする -->
```

* ファイルの削除
```
  rm samplet.txt                                                          <!-- samplet.txtを削除する -->
```



