# 概要
- 坂上が現段階で研究で使用している解析用コードをまとめ簡単に流用できるようにしたもの
- 基本的にはplexonで計測された.plxファイルから変換された.matファイル, TDT・オシロスコープで計測された.csvファイルを解析するために使用

## 目的用途
主に以下の用途に使用しています。
- matファイルで計測された全波形の加算平均
- 計測した信号波形の加工・描画・統計的解析


## 推奨環境
- python 3.9 

## 導入方法
- pipを使ってインストールできるようにするにはハードルが高いためsetup.pyを使用したインストール方法で運用することを考えています。
- 具体的な導入方法

```
# CLI(windowsだとgit bash推奨)上で以下のコマンドを打ってください
# ソースコードをおいておきたいディレクトリ下に移動した状態で
git pull https://github.com/smasa1112/Neuroplot_saka.git
cd Neuroplot_saka
py setup.py install
```

## 使用方法
編集中です…

