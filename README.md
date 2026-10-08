# moradou（配信専用）

もらいわすれ堂（株式会社フクギイロ）の公開サイト moradou.jp の配信先です。

**このリポジトリを直接編集しないでください。** 中身は
[allgroup-inc/hojo-hq](https://github.com/allgroup-inc/hojo-hq) の `site/` から
`scripts/deploy_moradou.py` が自動生成し、`moradou-deploy` ワークフローが
main への push ごとに丸ごと入れ替えます。手で直した分は次の配信で消えます。

- 本文・データの修正 → hojo-hq 側
- 公開設定（Pages / Custom domain）→ このリポジトリの Settings
- 経緯 → hojo-hq の `docs/議事_20260828_独自ドメインmoradou.md`
