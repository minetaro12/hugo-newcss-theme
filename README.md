<h1 align=center>Hugo new.css Theme</h1>

[Demo](https://minetaro12.github.io/hugo-newcss-theme)

デモサイトのソースは[examplesite](https://github.com/minetaro12/hugo-newcss-theme/tree/examplesite)ブランチにあります

## 使い方

```
# サイトの作成
$ hugo new site -f yml new-site
$ cd new-site
# テーマの追加
$ git clone https://github.com/minetaro12/hugo-newcss-theme themes/hugo-newcss-theme
# テーマの追加(Submodule)
$ git submodule add -b master https://github.com/minetaro12/hugo-newcss-theme themes/hugo-newcss-theme
# サンプル設定ファイルのコピー
$ cp themes/hugo-newcss-theme/example.config.yml config.yml
# テンプレートファイルのコピー
$ cp themes/hugo-newcss-theme/archetypes/default.md archetypes/default.md
# 記事の作成
$ hugo new posts/hello.md
```