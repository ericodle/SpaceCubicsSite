# Space Cubics Website

This repository contains the source code for the Space Cubics website, built using Jekyll and the Minimal Mistakes theme.

## Test locally

1.  Build the site and make it available on a local server. :

   ```bash
   bundle exec jekyll serve
   ```

## Project Structure
- _config.yml: Configuration file for Jekyll.
- _includes/: Contains reusable HTML components.
- _layouts/: Contains layout templates for the site.
- _pages/: Contains individual pages for the site.
- _sass/: Contains Sass stylesheets.
- assets/: Contains images, JavaScript, and CSS files.
- Gemfile: Specifies gem dependencies for the project.
- Rakefile: Contains tasks for building and maintaining the project.

# Main Goal

Jekyll を使用して Space Cubics Web サイトをより保守しやすい形式に移植する

# Benefits

- HTML や JavaScript を知らなくても保守が容易
- さまざまなホスティング サービスへの移行が容易になる
- 速度: Jekyll は静的 HTML ファイルを生成します。バックエンド処理やデータベース クエリがないため、動的に生成されたページよりも速く読み込まれます。
- セキュリティ: データベースやバックエンド スクリプトがなければ、静的サイトは SQL インジェクションやサーバー側エクスプロイトなどの攻撃に対して脆弱になりません。
- マークダウンのサポート: コンテンツをマークダウンで記述すると、生の HTML を扱わずに投稿やページの書式設定が簡単になります

# Structure

```python
.
├── assets
├── _includes
├── _layouts
├── _pages
│   ├── en
│   └── ja
└── _site
```

- _pages に移動するだけで、メイン サイトのページを編集できます (en=英語版、jp=日本語版)。
- _layouts には、ページの書式設定に使用される HTML と CSS が含まれています。
