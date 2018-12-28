# Type Theme

![Default Type Theme blog](https://user-images.githubusercontent.com/816965/30518919-d5978024-9bcd-11e7-81b3-3dd07e99a1f9.png)

A free and open-source [Jekyll](https://jekyllrb.com) theme. Great for blogs and easy to customize.

[Demo](https://rohanchandra.github.io/type-theme/)

## Usage

1. Fork and clone the [Type Theme repo](https://github.com/rohanchandra/type-theme): `git clone https://github.com/rohanchandra/type-theme`
2. [Install Jekyll](https://jekyllrb.com/docs/installation/): `gem install jekyll`
3. Install the theme's dependencies: `bundle install`
4. Customize the theme (see below)
5. Run the Jekyll server: `jekyll serve`


### Site configuration
The most common configurations, included here for guidance, are:

Jekyll website *without* a subpath (such as a GitHub Pages website for a given username):

```yml
# SITE CONFIGURATION
baseurl: ""
url: "https://username.github.io"
```

Jekyll website *with* subpath (like the Type Theme demo page):

```yml
# SITE CONFIGURATION
baseurl: "/sub-directory"
url: "https://username.github.io/"
```

Please configure this in `_config.yml` before using the theme.



### Math typesetting
Wrap math expressions with `$$` signs in your posts and make sure you have set the `katex` variable in `_config.yml` to `true` for math typesetting.

For inline math typesetting, type your math expression on the *same line* as your content. For example:

```latex
Type math within a sentence $$2x^2 + x + c$$ to display inline
```

For display math typesetting, type your math expression on a *new line*. For example:

```latex
$$
  \bar{y} = {1 \over n} \sum_{i = 1}^{n}y_i
$$
```

Type Theme makes use for [KaTeX](https://khan.github.io/KaTeX/) for typesetting.


## License
[The MIT License (MIT)](https://github.com/rohanchandra/type-theme/blob/master/LICENSE)
