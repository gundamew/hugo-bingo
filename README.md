# Bingo

A Hugo theme inspired by [Classic](https://themes.gohugo.io/hugo-classic/) theme, [XMin](https://themes.gohugo.io/hugo-xmin/) theme, and [Er](https://themes.gohugo.io/er/) theme.

![screenshot](https://github.com/gundamew/hugo-bingo/blob/master/images/screenshot.png)

## Installation

Inside the folder of your Hugo site:

```
$ cd themes
$ git clone git@github.com:gundamew/hugo-bingo.git
```

~~For more information read the official guide: [Install and Use Themes](https://gohugo.io/themes/installing-and-using-themes/).~~

Todo: [Use Hugo Modules](https://gohugo.io/hugo-modules/use-modules/)

## Features

### Use Google Analytics

This theme includes Hugo [internal template](https://gohugo.io/templates/internal/) for Google Analytics tracking. Provide your tracking ID in your configuration file to use it:

```toml
googleAnalytics = "UA-123-45"
```

### Use Gravatar

```toml
[params]

  [params.gravatar]
    email = "hugo@example.com"
```

### Custom navbar

```toml
[menu]

  [[menu.main]]
    identifier = "home"
    name = "Home"
    url = "/"
    weight = 10

  [[menu.main]]
    identifier = "posts"
    name = "Posts"
    url = "/posts"
    weight = 20
```

### Display social networks

You can put social network links on home page. It will sort by weight in ascending order, like navbar.

```toml
[params]

  [[params.social]]
    name = "github"
    url = "https://github.com/example"
    weight = 10

  [[params.social]]
    name = "twitter"
    url = "https://twitter.com/example"
    weight = 30

  [[params.social]]
    name = "linkedin"
    url = "https://www.linkedin.com/in/example"
    weight = 20
```

Available social icons:

* `bitbucket`
* `dribbble`
* `facebook`
* `github`
* `gitlab`
* `instagram`
* `keybase`
* `linkedin`
* `medium`
* `plurk`
* `stackexchange`
* `stackoverflow`
* `twitter`

### Custom date format

```toml
[params]
  dateFormat = "2006-01-02"
```

### Multiple languages

Example config:

```toml
defaultContentLanguage = "zh"
defaultContentLanguageInSubdir = true

[languages]

  [languages.en]
    weight = 10
    languageCode = "en-us"
    languageName = "English"
    contentDir = "content/en"

  [languages.fr]
    weight = 20
    languageCode = "fr-fr"
    languageName = "Français"
    contentDir = "content/fr"

  [languages.zh]
    weight = 30
    languageCode = "zh-tw"
    languageName = "中文（臺灣）"
    contentDir = "content/zh"

[menu]

  [[languages.en.menu.main]]
    identifier = "home"
    name = "Home"
    url = "/"
    weight = 10

  [[languages.en.menu.main]]
    identifier = "posts"
    name = "Posts"
    url = "/posts"
    weight = 20

  [[languages.fr.menu.main]]
    identifier = "home"
    name = "Maison"
    url = "/fr"
    weight = 10

  [[languages.fr.menu.main]]
    identifier = "posts"
    name = "Des postes"
    url = "/fr/posts"
    weight = 20

  [[languages.zh.menu.main]]
    identifier = "home"
    name = "首頁"
    url = "/zh"
    weight = 10

  [[languages.zh.menu.main]]
    identifier = "posts"
    name = "文章列表"
    url = "/zh/posts"
    weight = 20
```

And you have organize your posts like this:

```shell
.
└── content
    └── en
    │   ├── _index.md
    |   └── posts
    |       └── post-1.md
    ├── fr
    |   └── posts
    |       ├── post-1.md
    |       └── post-2.md
    └── zh
        ├── _index.md
        └── posts
            ├── post-1.md
            └── post-2.md
```

## Built With

* [Highlight.js](https://highlightjs.org/)
* [Simple Icons](https://simpleicons.org/)

## Contributing

Feel free to submit issues or pull requests.

## License

This theme is released under the MIT License. See [LICENSE](https://github.com/gundamew/hugo-bingo/blob/master/LICENSE).
