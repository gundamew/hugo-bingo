# Bingo

A Hugo theme inspired by [Classic](https://themes.gohugo.io/hugo-classic/) theme, [XMin](https://themes.gohugo.io/hugo-xmin/) theme, and [Er](https://themes.gohugo.io/er/) theme.

## Installation

Inside the folder of your Hugo site:

```
$ cd themes
$ git clone git@github.com:gundamew/hugo-bingo.git
```

For more information read the official guide: [Install and Use Themes](https://gohugo.io/themes/installing-and-using-themes/).

## Usage

### Change highlighting style

This theme use Chroma as syntax hightlighter. If you want to change the highlighting style, run command below to regenerate style sheet:

```
$ hugo gen chromastyles --style=solarized-light > syntax.css
```

For more information read the official guide: [Syntax Highlighting](https://gohugo.io/content-management/syntax-highlighting/).

### Add social networks

You can put social network links on footer:

```toml
[menu]

  [[menu.social]]
    identifier = "github"
    name = "GitHub"
    url = "https://github.com/"
    weight = 10

  [[menu.social]]
    identifier = "linkedin"
    name = "LinkedIn"
    url = "https://www.linkedin.com/"
    weight = 20

```

## Contributing

Feel free to submit issues or pull requests.

## License

This theme is released under the MIT License. See [LICENSE](https://github.com/gundamew/hugo-bingo/blob/master/LICENSE).
