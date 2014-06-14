imgodr
======

写真を撮影日(EXIF:0x9003)で並べ替え(rename)ます。

たとえば

- IMG145623.JPG
- xxxx - 02.jpg
- xxxx - 02 - コピー.jpg

とあったとき

- 2013年03月22日 09時55分09秒.JPG
- 2014年01月10日 23時06分42秒.jpg
- 2014年01月10日 23時06分42秒 (1).jpg

のように名前が変化します。

EXIF の 0x9003 を読み取れなかったファイルは無視します。
