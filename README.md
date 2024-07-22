# Anubis2 Theme for Hugo 

This theme is a fork of the original Anubis2 theme created by [junyi](https://github.com/junyi). It builds upon the features of the original theme and adds additional functionality and improvements.

## Highlighted Features

- Multilingual
- Dark / Light mode (Automatic switch based on system settings)
- Table of Contents
- Comment Support (Giscus, Disque, ISSO, Utterances, GraphComment)
- Analytics (Google, Umami)
- RSS feeds
- Mobile Support
- [Full Features](wiki/Full-Features)

## Installation & Configuration

You need to install an extended version of Hugo to run this theme.

For more information read the [official setup guide of Hugo](https://gohugo.io/installation/).

### Install theme as Git Submodule

Inside the folder of your Hugo site, run:

```bash
git submodule add https://github.com/amandamata/hugo-theme-anubis2.git themes/anubis2
```

That's all, let's configure anubis2.

### Configure your site

Don't be panic, configure Anubis2 is really **simple**.

**This is the minimum configuration:**

```toml
languageCode = "en-us"
theme = "anubis2"
title = "Your Site's Name"

[author]
name = "Your Name"

[markup.goldmark.renderer]
unsafe = true # Enable unsafe mode to have a better experience

[markup.highlight]
style = 'base16-snazzy' # Highlight.js style
```

## Run your site

In order to see your site, run Hugo's built-in local server.

```bash
hugo server
```

Now enter [`http://localhost:1313`](http://localhost:1313/) in the address bar of your browser to open your site.

## Update Anubis2 to the latest version

In your Hugo site folder, run this command:

```bash
git submodule update --remote
```

## Contributing

If you find a bug or have an idea for a feature, feel free to write an [issue](https://github.com/amandamata/hugo-theme-anubis2/issues) or make a PR.
