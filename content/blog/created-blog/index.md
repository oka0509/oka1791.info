---
title: ブログを作りました
date: "2023-03-26T23:30:32.169Z"
tags: [雑記, プログラミング]
---

Gatsby.js でブログを作りました。間違えているところなどあったら教えてくれるとうれしいです。

```toc
```

## Gatsby.js

---

Gatsby.jsはReactベースのGraphQLを使った静的サイトジェネレータです。Reactでブログ作りたいというのを元々考えていて、これとNext.jsのどっちを使うか迷ったのですが、作りたいのが静的なブログ+サイトがめっちゃ早いらしいのでこっちにしてみました。テンプレが色々とあって、自分は[gatsby-starter-blog](https://www.gatsbyjs.com/starters/gatsbyjs/gatsby-starter-blog)に機能をちょっと追加して作成しました。

## 使ったライブラリ 

---

### react-bootstrap

BootstrapのReact版らしいです。機能がめちゃめちゃ充実していて、レスポンシブ対応もちょっと設定するだけで作れちゃいます。すごい。

### React Icons

FontAwesomeその他etcがまとまっているライブラリです。リンク用のアイコンで使いました。読書メーター用のアイコンは見つからなかったので、それだけSVGを取ってきて使いました。

## 感想

---

Reactは前に使ったことがあったのである程度はいけるかなと思って始めてみたものの、GraphQL周りでデータ取ってきたりするところでめちゃめちゃに苦戦しちゃいました...~~とはいえコピペしてきたクエリ貼ったら動いたのでOKです。インターネット最高！~~ 触っているうちにだんだん楽しくなってきたので、慣れてきたらすごく気持ちいいのかなと思います。GraphQL1回ちゃんと勉強したくなったんですが、今のところこれ以外だとあまり使う機会なさそう...
