# FirstTest
最初のコード

## markdownについて
markdownというのは、いろんなところで使われているWiki記述的なフォーマットである。
## 変更とコミットとプッシュについて
- 変更の履歴はテキストファイルの行番号ごとに行われる。
このため、行番号を持たないバイナリファイルの場合は
差分で保存されるのではなく、コピーがどんどん保存され、
上限の１００ＭＢをすぐ超えてしまうので除外しましょう。
--- 例えばitch.ioなどでダウンロードしてきたアセットをgitHub管理下においてしまうとまずいことになる。
+++ ライセンスの問題。
+++ zipや大量のpngがバージョンの管理に含まれてしまうと、サイズを圧迫し、本来必要なデータ
^   をアップロードすることができなくなります。
--- チーム間で、素材を共有する場合はＵＲＬをテキスト保存し、そこからダウンロードするか、どのように使うかどこに配置するか記載したテキストバージョン管理に含める。
