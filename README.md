# DeskGROW 3Dプリント工房（desk-grow.jp）

GitHub Pages（Jekyll）で公開しているサイトです。ファイルを更新すると、数分で自動的にサイトに反映されます。

## ブログ記事の追加方法
1. `_posts` フォルダを開き、「Add file → Create new file」を押す
2. ファイル名を `2026-11-20-kiji-no-namae.md` の形にする（日付-英数字の名前.md）
3. 先頭に下の設定を書き、その下に本文を書く
4. 「Commit changes」で保存

```
---
layout: post
title: 記事のタイトル
description: 検索結果に出る説明文（80〜120字）
date: 2026-11-20 09:00:00 +0900
category_ja: あるある        # あるある／制作事例／ストーリー／事業の話 など
cat: ARU-ARU                 # カードに出る英字ラベル
cover: beige                 # green / beige / blue のどれか
cover_text: "カードに出す\n2行の見出し"
tags: [3Dプリンター, 3Dプリント]
repost: true                 # スキルマーケットのブログからの再掲載なら true
original_url: https://...    # 元記事のURL（あれば）
---
```

本文の書き方
- 見出し：行頭に `## `
- 「運営者のひとこと」：行頭に `> **運営者のひとこと**` と書き、次の行から `> ` に続けて本文
- 箇条書き：行頭に `- `

## 主なファイル
- `index.html`：トップページ（LP）
- `legal/`：特定商取引法に基づく表記
- `privacy/`：プライバシーポリシー
- `assets/img/`：画像（制作事例の写真を差し替えるときはここ）
- `CNAME`：独自ドメイン（desk-grow.jp）の設定。消さないこと
