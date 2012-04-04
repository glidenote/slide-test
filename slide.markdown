2012年のプレゼンはgithub Pages + markdown2impressで決まり
==========
2012-04-04  
@glidenote

プレゼン作成に使用するソフト
----------

下記ソフトを事前に導入

 * [yoshiki/markdown2impress](https://github.com/yoshiki/markdown2impress)
 * [defunkt/hub](https://github.com/defunkt/hub)
 * [glidenote/hub-zsh-completion](https://github.com/glidenote/hub-zsh-completion)

拙作の`hub-zsh-completion`は無くても作業は出来ます。

markdownで下書きを作成
----------

 * 作業用ディレクトリを作成
 * その中にmarkdown形式でプレゼンの下書きを用意


markdown2impressで変換
----------

 * 下書きを`markdown2impress`でindex.htmlに変換
 * css,jsも合わせて生成される


hub(git) createでリポジトリを作成
----------

 * hubコマンドを利用して、githubにリポジトリを作成
 * ブラウザからリポジトリを作成してもOK
 * hub-zsh-completionを利用していれば`git create`


gh-pagesブランチを作成してpush
----------

 * github pagesを利用するために、`gh-pages`というブランチを用意
 * 更新作業や編集作業は`maser`ではなく`gh-pages`で行う
 * できあがったら`git push origin gh-pages`でpush


github pagesの表示確認
----------
 
 * http://username.github.com/reponame という形式でページができあがる
 * ブラウザで動作の確認


まとめ
----------
 
 * ブラウザでの表示確認以外は全部コマンドラインで行える
 * プレゼン資料がmarkdownで書ける
 * markdownを覚えないと利用出来ない

と、こんな感じのことがサクサクと出来ます
----------


