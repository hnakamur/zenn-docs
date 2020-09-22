---
title: "Zennのスラッグ（slug）とは"
emoji: "🤔"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["zenn"]
published: true
---

slug（スラッグ）は、記事や本のユニークなIDのようなものです。スラッグが`example-article`の場合、記事のURLは

```
https://zenn.dev/ユーザー名/articles/example-article
```

となります。

# slugの指定
slugは基本的にランダムで作成されます。[コンテンツのGitHubリポジトリ管理](/zenn/articles/connect-to-github.md)を行っている場合のみ、slugを任意に指定できます。

# slugの注意点
1. slugはサイト全体で（記事や本などのコンテンツの種類ごとに）ユニークでなければなりません
2. slugは**半角英数字（a-z0-9）とハイフン（-）の12〜50字の組み合わせ**にする必要があります
3. slugは一度zenn.dev上で作成されたら変更できません
