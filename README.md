# Kodatuno

## Kodatuno について
Kodatuno は，金沢大学マンマシン研究室で開発されているオープンソースのCAMカーネルです．
本家は <http://www-mm.hm.t.kanazawa-u.ac.jp/research/kodatuno/>

## 本リポジトリについて
main ブランチは，本家からダウントードしたソースコードでコミットしたものです．  
Visual Studio ブランチは，Visual Studio 2022 でビルドできるようにしたソリューションファイルを管理しています．  
Kodatuno.vs フォルダ配下には，本家の Src/GE フォルダにあるコード一式をコピーし，さらにNCVC用のパッチを当ててビルドできるようにしています．  
（シンボリックリンクは Git for Windows ではオプションを設定しないと使えないのでコピーしています）

## Visual Studio でのビルド方法
Visual Studio ブランチをチェックアウトし，Kodatuno.slh を開いてください．
ビルドに必要な設定はできているはずです．
