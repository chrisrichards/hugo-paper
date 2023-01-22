<div align="center">
<h1>Paper <sup><sup><sub>6.7</sub></sup></sup> for chrisrichards.co.uk</h1>

Demo → [hugo-paper.vercel.app](https://hugo-paper.vercel.app/)

<hr />

A simple, clean, flexible Hugo theme. Ported to and customized for [chrisrichards.co.uk](https://chrisrichards.co.uk)

⚡️ Fast | 📸 Fluent | 🫙 Smooth

</div>

---

## Overview

![](https://raw.githubusercontent.com/chrisrichards/hugo-paper/main/images/screenshot.png)
![](https://raw.githubusercontent.com/chrisrichards/hugo-paper/main/images/screenshot_dark.png)
![](https://raw.githubusercontent.com/chrisrichards/hugo-paper/main/images/screenshot_mobile.png)

## Install

Inside the folder of your Hugo project, run:

```bash
git submodule add https://github.com/chrisrichards/hugo-paper themes/paper
```

Open `config.toml`, change `theme` to `"paper"`:

```toml
theme = "paper"
```

For more information, please read the [official guide](https://gohugo.io/getting-started/quick-start/#step-3-add-a-theme) of Hugo.

## Options

Available options to `config.toml`:

```toml
disqusShortname = 'YOUR_DISQUS_SHORTNAME'   # use disqus comments

[params]
  # color style
  color = 'linen'                           # linen, wheat, gray, light

  # header social icons
  twitter = 'YOUR_TWITTER_ID'               # twitter.com/YOUR_TWITTER_ID
  github = 'YOUR_GITHUB_ID'                 # github.com/YOUR_GITHUB_ID
  instagram = 'YOUR_INSTAGRAM_ID'           # instagram.com/YOUR_INSTAGRAM_ID
  mastodon = 'YOUR_MASTODON_LINK'           # e.g. 'https://mastodon.instance/@xxx'
  rss = true                                # show rss icon

  # home page profile
  avatar = 'GRAVATAR_EMAIL'                 # gravatar email or image url
  name = 'YOUR_NAME'
  bio = 'YOUR_BIO'


  # misc
  disableHLJS = true                        # disable highlight.js
  monoDarkIcon = true                       # show monochrome dark mode icon
  gravatarCdn = 'GRAVATAR_CDN_LINK'         # e.g. 'https://cdn.v2ex.com/gravatar/'
  graphCommentId = "YOUR_GRAPH_COMMENT_ID"  # use graph comment (disqus alternative)
```

## License

[MIT License](https://github.com/chrisrichards/hugo-paper/blob/main/LICENSE) (c) [Chris Richards](https://chrisrichards.co.uk/)
