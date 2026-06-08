# 漢字でGOGO! FAQ テンプレート

GitHub Pagesなどで公開できる、Markdown更新式のFAQサイトひな形です。

## ファイル構成

```txt
.
├─ index.html
├─ faq.md
├─ .nojekyll
└─ img/
   └─ Mode_bg.png
```

## 使い方

1. このフォルダの中身をGitHubリポジトリに置きます。
2. `faq.md` の文章を編集します。
3. 画像を使う場合は `img/` に入れ、Markdownで `![説明](img/ファイル名.png)` と書きます。
4. GitHubの **Settings → Pages** から公開ブランチを選びます。

## ローカル確認

`index.html` を直接ダブルクリックすると、ブラウザの制限で `faq.md` を読み込めない場合があります。  
その場合は、VS CodeのLive Serverなど、簡易Webサーバー経由で確認してください。

## メモ

- `index.html` は `faq.md` を読み込んでFAQカードとして表示します。
- `###` の見出しが1つのFAQ項目として扱われます。
- `##` の見出しは目次に表示されます。
- 背景画像は `img/Mode_bg.png` を参照しています。
