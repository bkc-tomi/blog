# 使い方

`./mkarticle.sh ファイル名`でマークダウンファイルを作成(ファイル名は必ず入れる)

初めての場合は、`chmod 755 mkarticle.sh`をする

- title
- category
- topics
- published

を入力する。

以降に記事を書いていく。

## title
記事のタイトル(必須)

## category
記事のカテゴリー（必須）

現在検討中

そもそもtopicsで検索可能にする予定なので必要ないかもしれない。ユーザーが記事を見つけやすい方を最終的には残す。
そのため、現在は必須

## topics
検索用のタグ。配列で複数指定可能

## published
本番環境では、trueのものを表示する
