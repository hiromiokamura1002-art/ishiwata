# 石綿調査者ドリル（法務ページとサポート）

資格の学習アプリ「石綿調査者ドリル」（一般建築物石綿含有建材調査者の修了考査にそなえる問題集）の、プライバシーポリシー・利用規約・特定商取引法に基づく表記・サポートのページです。非公式のアプリで、講習機関・公的機関とは関係がありません。

## 4 つのページ

- サポート：https://hiromiokamura1002-art.github.io/ishiwata/support.html
- プライバシーポリシー：https://hiromiokamura1002-art.github.io/ishiwata/legal/privacy.html
- 利用規約：https://hiromiokamura1002-art.github.io/ishiwata/legal/terms.html
- 特定商取引法に基づく表記：https://hiromiokamura1002-art.github.io/ishiwata/legal/tokushoho.html

入口（https://hiromiokamura1002-art.github.io/ishiwata/）は index.html です。

## 公開のしかた（GitHub Pages）

1. GitHub に公開（Public）のリポジトリ `hiromiokamura1002-art/ishiwata` を作り、このフォルダの中身を全部入れる
2. リポジトリの Settings → Pages を開く
3. 「Build and deployment」の Source を **Deploy from a branch** にする
4. Branch を **main**、フォルダを **/ (root)** にして Save
5. 1〜5 分待って、上の 4 つのページが開くことを確かめる

## 文面を直すとき

ここのファイルは手で直さず、アプリのリポジトリ（ishiwata-app）の `src/lib/legalTexts.ts` を直して `npm run gen:legal` で書き出し、`docs/index.html`・`docs/support.html`・`docs/legal/*.html` をここに写します（アプリの中の文面と食い違わないように）。

問い合わせ：elplancho.cheese@gmail.com
