# TIL
日々の勉強記録をストックする

## 仕組み
- TILs/*/以下のディレクトリに更新があると、[カレンダーページのGiHubリポジトリ](https://github.com/IzmYuta/TIL_pages)の``_posts``以下と同期する
- こちらのリポジトリではイベントをトリガーする
- 向こうのリポジトリがイベントを検知すると同期処理が行われる
- 詳しくは[こちらの記事](https://zenn.dev/tak_iwamoto/articles/c4e8677f2a50af)を参照
 
## 保存形式・注意事項
- TILs/*/に``YYYY-MM-DD-タイトル.md``の形式で保存する。
- TILs/直下だとファイルを検知しないのでもう一階層ぶん”だけ”下のディレクトリで作成すること(それ以下の階層で作ると面倒なことになる)

カレンダーページ：https://izmyuta.github.io/TIL_pages/

カレンダーページのGiHubリポジトリ：https://github.com/IzmYuta/TIL_pages
