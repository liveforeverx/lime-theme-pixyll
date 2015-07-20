# Pixyll

Pixyll is a simple, beautiful theme for [Lime](https://github.com/liveforeverx/lime)
Based on [Pixyll for Hugo](https://github.com/azmelanar/hugo-theme-pixyll), which is based on based on [Pixyll for Jekyll](https://github.com/johnotander/pixyll)

## Features

- Basic tag support.
- Disqus comments supported.
- Google Analytics supported.
- Social links (currently only for twitter, facebook).
- [Formspree](http://formspree.io/) for contanct form.
- Pagination support.

Example config:

```toml
languageCode = "en-us"
content_dir = "content"
publish_dir = "public"
builddrafts = false
base_url = ""
canonifyurls = true
title = "Pixyll"
author = "admin"
theme = "pixyll"

[indexes]
  category = "categories"
  tag = "tags"

[params]
  search_engine = true
  google_analytics_id = "XX-XXXXXXXX-X"
  twitter_username = "username"
  disqus_shortname = "sitename"
  paginate = true
```

![Pixyll Screenshot](https://raw.githubusercontent.com/azmelanar/hugo-theme-pixyll/master/images/tn.png)
