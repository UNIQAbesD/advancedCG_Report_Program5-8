# advancedcg_report
筑波大学情報学群情報メディア創成学類の授業「アドバンストCG」の第5回～第8回のレポートのためのベースコード公開用リポジトリです．
This is a repository for the lecture course "Advanced Computer Graphics" in University of Tsukuba. 

## 各フォルダについて
* Advanced05～Advanced08 : 第5回～第8回の授業課題のベースプログラムが置いてあります．
* bin : 実行用フォルダ．DLLや実行時に参照する画像やモデルファイル，シェーダーなどが置いてあります．
* include : 第5回～第8回の授業課題で必要となるヘッダファイルが置いてあります．VisualStudio以外でコンパイルする際はincludeをインクルードフォルダとして追加するか，include内の*.hファイルをフォルダ構造そのままにcppファイルのあるところにコピーするようにしてください．
* vc-x64-lib-common : Visual Studio 共通のライブラリファイル
* vc-x64-libs : バージョン別のライブラリファイル
