<div align="center">
<h1>Paper <sup><sup><sub>5.1</sub></sup></sup></h1>

Demo → [pushyzheng.com](https://pushyzheng.com/)

<hr />

A simple, clean, flexible Hugo theme.

⚡️ Fast | 🦋 Fluent | 🪀 Smooth

</div>

---

## Links

Product Hunt: [producthunt.com/posts/hugo-paper](https://www.producthunt.com/posts/hugo-paper)

Hugo themes: [themes.gohugo.io/hugo-paper](https://themes.gohugo.io/hugo-paper/)

## Overview

![](./images/screenshot.png)
![](./images/screenshot_dark.png)

## Install

Inside the folder of your Hugo project, run:

```bash
git submodule add https://github.com/nanxiaobei/hugo-paper themes/paper
```

Open `config.toml`, change `theme` to `"paper"`:

```toml
theme = "paper"
```

For more information, please read the [official guide](https://gohugo.io/getting-started/quick-start/#step-3-add-a-theme) of Hugo.

## Options

Available options to `config.toml`:

```toml
[params]
  disableHLJS = true                         # don't use highlight.js
  twitter = 'YOUR_TWITTER_ID'                # twitter.com/YOUR_TWITTER_ID
  github = 'YOUR_GITHUB_ID'                  # github.com/YOUR_GITHUB_ID
  instagram = 'YOUR_INSTAGRAM_ID'            # instagram.com/YOUR_INSTAGRAM_ID
```

giscus, for example: 

```toml
[params]
  giscus-repo = pushyzheng/blog
  giscus-repo-id = R_kgDOIVqytA
  giscus-mapping = url
```

add 'comment = true' in metadata:

```yaml
---
title: ...
comment: true
---
```

## License

[MIT License](https://github.com/nanxiaobei/hugo-paper/blob/master/LICENSE) (c) [nanxiaobei](https://lee.so/)

## FUTAKE

Try [**FUTAKE**](https://sotake.com/f) in WeChat. A mini app for your inspiration moments. 🌈

![FUTAKE](https://s3.jpg.cm/2021/09/21/IFG3wi.png)
