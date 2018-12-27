# Bingo

A Hugo theme inspired by [Classic](https://themes.gohugo.io/hugo-classic/) theme, [XMin](https://themes.gohugo.io/hugo-xmin/) theme, and [Er](https://themes.gohugo.io/er/) theme.

![screenshot](https://github.com/gundamew/hugo-bingo/blob/master/images/screenshot.png)

## Installation

Inside the folder of your Hugo site:

```
$ cd themes
$ git clone git@github.com:gundamew/hugo-bingo.git
```

For more information read the official guide: [Install and Use Themes](https://gohugo.io/themes/installing-and-using-themes/).

## Usage

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
    icon = "github"
    url = "https://github.com/example"
    weight = 10

  [[params.social]]
    icon = "twitter"
    url = "https://twitter.com/example"
    weight = 30

  [[params.social]]
    icon = "linkedin"
    url = "https://www.linkedin.com/in/example"
    weight = 20
```

Available social icons:

* `bitbucket`
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

## Built With

* [Highlight.js](https://highlightjs.org/)
* [Simple Icons](https://simpleicons.org/)

## Contributing

Feel free to submit issues or pull requests.

## License

This theme is released under the MIT License. See [LICENSE](https://github.com/gundamew/hugo-bingo/blob/master/LICENSE).
