# docomo-cycle.com

docomo-cycle.comで公開するコンテンツ置き場です。写真galleryになり、画像ファイルも格納する事になりますが大きな写真は迷惑なのできっちりリサイズをお願いします。

## resize規定
ImageMagick環境にて下記コマンドにてリサイズしてください。

   `mogrify -strip -format jpg -unsharp 0.125x1.0+1+0.05 -quality 90 -modulate 105 -contrast -resize 1280x\> *.*`

