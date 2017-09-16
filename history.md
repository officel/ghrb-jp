# 作業履歴というメモ

* [README.md](https://github.com/officel/ghrb-jp/blob/master/README.md)
  * リポジトリの説明等を記載するファイル
  * github 上でリポジトリを新規作成する際に自動的に作成することができる

* [.github/CONTRIBUTING.md](https://github.com/officel/ghrb-jp/blob/master/.github/CONTRIBUTING.md)
  * 貢献について記載するファイル
  * 参照 [Setting guidelines for repository contributors - User Documentation](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
  * テンプレートがないので記載すべき内容を精査する。上記リンク先に他の OSS へのリンクがある

* [.github/CODE_OF_CONDUCT.md](https://github.com/officel/ghrb-jp/blob/master/.github/CODE_OF_CONDUCT.md)
  * 行動規範について記載するファイル
  * 参照 [Adding a code of conduct to your project - User Documentation](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/)
  * github 上で作成してテンプレートから選択することができる
  
* [LICENSE](https://github.com/officel/ghrb-jp/blob/master/LICENSE)
  * ライセンスに記載するファイル
  * このファイルはリポジトリのルートディレクトリに置くのが望ましい（らしい）
  * 参照 [Adding a license to a repository - User Documentation](https://help.github.com/articles/adding-a-license-to-a-repository/)
  * github 上でリポジトリを新規作成する際に選択することができる
  * （後から）github 上で作成してテンプレートから選択することができる
  * README.md 最下部にリンクを用意するのは任意（らしい）
  * [Licensing a repository - User Documentation](https://help.github.com/articles/licensing-a-repository/)
  * ライセンスファイルを置くと、github 上の overall-summary に選択したライセンス名が表示される

* 上記４つのファイルを作成すると、[Community](https://github.com/officel/ghrb-jp/community) ページが100%になる
* github 上でテンプレートの選択可能なファイルは、後から github 上で編集することで選択しなおすことができる
* リポジトリルートをシンプルに保ちたいので置いていいファイルは .github ディレクトリに配置する

* [.github/SUPPORT.md](https://github.com/officel/ghrb-jp/blob/master/.github/SUPPORT.md)
  * サポート、ヘルプ等を記載するファイル
  * 参照 [Adding support resources to your project - User Documentation](https://help.github.com/articles/adding-support-resources-to-your-project/)
  * 例 [atom/SUPPORT.md at master · atom/atom](https://github.com/atom/atom/blob/master/SUPPORT.md)
  * 配置すると、 github 上で ISSUE を作成する際にリンクが表示される（はずなんだけど機能しない。~~.githubディレクトリだから？~~ ルートに置いてもダメだった）
  * 比較的新しい機能みたい [SUPPORT file support](https://github.com/blog/2400-support-file-support)

* [.github/ISSUE_TEMPLATE.md](https://github.com/officel/ghrb-jp/blob/master/.github/ISSUE_TEMPLATE.md)
  * 課題の新規作成用テンプレートファイル
  * 課題作成時に記載して欲しいことをあらかじめテンプレート化しておくことができる
  * 参照 [Creating an issue template for your repository - User Documentation](https://help.github.com/articles/creating-an-issue-template-for-your-repository/)

* [.github/PULL_REQUEST_TEMPLATE.md](https://github.com/officel/ghrb-jp/blob/master/.github/PULL_REQUEST_TEMPLATE.md)
  * プルリクエストの新規作成用テンプレートファイル
  * プルリク作成時に記載してほしいことをあらかじめテンプレート化しておくことができる
  * ドキュメントでは issue_template と同様に not case sensitive と書いてあるけど、こちらはドキュメントが大文字で例示されている
  * 参照 [Creating a pull request template for your repository - User Documentation](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/)

* ISSUE 作成時のリンクが出現しないので、日本語を削除して英語のみに修正してみたが解消しなかった
* Contact Github ページからヘルプを投げてみた。返事待ち

