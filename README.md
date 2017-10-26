# 英語ページの編集方法
- 基本的には Rmd なのでマークダウンで編集します。
- .Rproj を使って RStudio で開いておけば Build タブの `Build Website` をクリックするとすべてのページがレンダリングされます。 `rmarkdown::render_site()` でもOK。
- `_site.yml` など全体のデザインや構成については [公式サイト](http://rmarkdown.rstudio.com/rmarkdown_websites.html) か [kazutan さんの資料](https://kazutan.github.io/RmdSite_tuto/)を参照。