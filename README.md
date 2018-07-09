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

### Add social networks

You can put social network links on home page:

```toml
[params]
  email = "username@domain"  # for Gravatar
  github = "github_username"
  linkedin = "linkedin_username"
  medium = "medium_username"
  twitter = "twitter_username"
  facebook = "facebook_username"
  instagram = "instagram_username"
```

## Built With

* [Highlight.js](https://highlightjs.org/)
* [Simple Icons](https://simpleicons.org/)

## Contributing

Feel free to submit issues or pull requests.

## License

This theme is released under the MIT License. See [LICENSE](https://github.com/gundamew/hugo-bingo/blob/master/LICENSE).
