---
layout: default
---

# Mezumona Kosaki
フルネームは「狐崎めずもな」です。大抵は「めずもな」と呼ばれます。

## Portfolio
[Portfolio](portfolio)

## Accounts
- GitHub: @mezum
- Qiita: [mezumona](http://qiita.com/mezumona)
- Stargzr: [mezumona](https://stargzr.net/users/mezumona)
- Twitter: [@mezumona](https://twitter.com/mezumona)
- SoundCloud: [mezum](https://soundcloud.com/mezum)

## Novels
- [音の色](novels/tonecolor)

## blog
[全ての記事はこっちから。](blog)
### 最新の 5 件
{% for post in site.posts limit:5 %}
- [{{ post.date | date_to_string }} : {{ post.title }}]({{ post.url }})
{% endfor %}
