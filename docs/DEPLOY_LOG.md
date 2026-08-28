# Deploy log

- 日時: 2026-08-28 JST
- 公開コミット: `3f7b02a6c781fb351fb54b734f768bc84e9554e0`
- `index.html` SHA-256: `4e1793a9d7c70f94eed2822656234a92197530e4f81d778ede087dd7c2652bb2`
- 公開URL: https://gen-ryu-system.github.io/salesanchor-info/
- 検証A: HTTP 200
- 検証B: 配信HTML SHA-256 一致
- 検証C: https://gen-ryu-system.github.io/inventory-info/ HTTP 200

## ロールバック

- 内容を戻す: `git revert <SHA>`
- 公開停止: `gh api repos/GEN-RYU-System/salesanchor-info/pages -X DELETE`
- リポジトリ削除は提案のみとし、人間が判断する。
