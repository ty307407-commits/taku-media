# taku-media

「たく」(@taku_taku_taku7) の Threads 投稿に添える画像の置き場。

Threads API は画像ファイルを受け取らず、外部から到達できる公開URLを取りに行く方式のため、
投稿の直前に `~/x-affiliate/threads/post_due.mjs` がここへ画像を push し、その raw URL を Threads に渡す。
中身は全て公開投稿に載せた（載せる）画像で、人が手で触ることはない。

- 置き方: `YYYY/MM/<sha1先頭8>-<元のファイル名>`（同じ画像は同じ名前になり、二重に上がらない）
- URL: `https://raw.githubusercontent.com/ty307407-commits/taku-media/main/YYYY/MM/<file>`
