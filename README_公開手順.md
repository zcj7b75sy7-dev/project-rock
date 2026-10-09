# PROJECT ROCK — BLK テスト版 PWA

## iPhoneだけで公開する手順（GitHub Pages）

1. ZIPをiPhoneの「ファイル」アプリで展開。中の `index.html`, `app.js`, `vehicles.js`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` を使います。
2. Safariで https://github.com にアクセスし、無料アカウントを作成。
3. 新規Publicリポジトリ `project-rock` を作成。
4. リポジトリの「Add file」→「Upload files」で上記7ファイルをすべてアップロードしてコミット。iPhoneで項目が見つからない場合はSafariの「デスクトップ用Webサイトを表示」を使います。
5. リポジトリ「Settings」→「Pages」→「Build and deployment」→「Deploy from a branch」→「main」「/(root)」→「Save」。
6. 公開URL `https://GitHubユーザー名.github.io/project-rock/` をSafariで開く。反映には数分かかる場合があります。
7. Safariの共有→「ホーム画面に追加」でアプリ風に使用。最初にオンラインで開いてからオフライン利用を確認してください。

## 注意

- GitHub Pagesは一般公開です。URLを知る人以外にも閲覧可能です。秘密の仲間限定アクセス制御はありません。
- マイセッティングは各端末のブラウザ内に保存。機種変更・サイトデータ削除では消える可能性があります。JSON書き出しでバックアップできます。
- 車種データは開発用参考値。年式・MT/AT、純正ギアの正確性、社外T/Fとデフの物理適合は未監査です。実車整備に使用する前に検証してください。
- JA11ケース交換のHI/LOW数値は計算比較用で、装着できるという意味ではありません。
- 公式のApp Storeアプリではありません。PWAを先にテストするための配布版です。
- 更新時はキャッシュの反映に時間がかかる場合があります。
