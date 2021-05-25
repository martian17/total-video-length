# total-video-length

この動画を元に使いやすいオールインワン実行可能bashコマンドファイルを作ってみました。
https://www.youtube.com/watch?v=bsq2YY-XAEo

## 使い方
ターミナルにて
```bash
$ git clone https://github.com/martian17/total-video-length.git
# videolenファイルを整理したいディレクトリーに移動させるか、/usr/binなどのコマンド置き場に移動させ、使ってください。
$ mv videolen ~/Videos/
```
videolenコマンドは2つの引数を取ります。1つ目は探索場所、2つ目は拡張子です。
例
```bash
./videolen . mp4
```
