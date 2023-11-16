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
* ディレクトリ階層の移動（サンプルディレクトリ : sampledir）
```
cd sampledir  <!-- 参照階層内の対象ディレクトリに降りる -->
cd ../        <!-- 参照階層からひとつ上のディレクトリに上がる -->
```
* ディレクトリの作成（サンプルディレクトリ : sampledir）
```
mkdir sampledir  <!-- 参照階層内にsampledirディレクトリを作成する -->
```
* ファイルの作成（サンプルファイル）
```
touch samplet.txt    <!-- 参照階層内にテキストファイルsampletを作成する -->
touch samplej.java   <!-- 参照階層内にJavaファイルsamplejを作成する -->
```
* ファイルの移動（サンプルファイル : samplet.txt）
* ファイル名の変更も行うことができる
```
mv samplet.txt sampledir      <!-- samplet.txtをsampledirディレクトリに移動する -->
mv samplet.txt samplexx.txt   <!-- ファイル名をsampletからsamplexxに変更する -->
```
* ファイルのコピー（サンプルファイル : samplet.txt）
```
cp samplet.txt sampledir  <!-- samplet.txtをsampledirディレクトリにコピーする -->
```



