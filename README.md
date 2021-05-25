# total-video-length

この動画を元に使いやすいオールインワンの実行可能ばbashコマンドファイルを作ってみました。
https://www.youtube.com/watch?v=bsq2YY-XAEo

## 使い方
ターミナルにて
```bash
$ git clone https://github.com/martian17/total-video-length.git
# videolenファイルを整理したいディレクトリーに移動させるか、/usr/binなどのコマンド置き場に移動させ、使ってください。
$ mv videolen ~/Videos/
```
videolenコマンドは2つの引数を取ります。1つ目は探索場所、2つ目は拡張子です。
実行例
```bash
$ ./videolen . mp4
./3x32.mp4: 16.000000 seconds
./3x3.mp4: 20.167000 seconds
./instantcountertest.mp4: 17.518000 seconds
./cheaprep1.mp4: 74.367000 seconds
./shakyprogress.mp4: 82.167000 seconds
./cheaprep.mp4: 139.967000 seconds
./servertest.mp4: 16.333333 seconds
./3x31.mp4: 25.167000 seconds
./risashine.mp4: 9.866667 seconds

401.553000 seconds
0 days, 0 hours, 6 minutes, 41.553000 seconds
```
