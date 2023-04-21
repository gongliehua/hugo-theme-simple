# hugo-theme-simple

## Install

1. Copy the theme in your site:

```
git submodule add https://github.com/gongliehua/hugo-theme-simple themes/hugo-theme-simple
```

2. Edit your `config.toml`:

```
theme = 'hugo-theme-simple'
paginate = 30

[params]
  description = ''
  keywords = []

[menu]
[[menu.main]]
  name = 'Home'
  pageRef = '/'
  weight = 10
[[menu.main]]
  name = 'Archives'
  pageRef = '/archives'
  weight = 20
[[menu.main]]
  name = 'About'
  pageRef = '/about'
  weight = 30
```
