---
title: タグ
intro: 'Git タグは [Gitリファレンス](/rest/reference/git#refs)に似ていますが、変更されることがないところを指す Gitコミットです。'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
---

Git タグは、特定のリリースを指すときに役立ちます。 これらのエンドポイントを使用すると、{% data variables.product.product_name %} 上の Git データベースに対して [タグオブジェクト](https://git-scm.com/book/en/v1/Git-Internals-Git-References#Tags)の読み書きができます。 Git タグ API は、[アノテーションされたタグオブジェクト](https://git-scm.com/book/en/v1/Git-Internals-Git-References#Tags)のみをサポートし、軽量タグはサポートしません。
