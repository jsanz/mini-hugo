# A minimal Hugo theme

This is simple theme for Hugo, just with only the minimal components and meant to serve static pages. This is not a theme for a blog or a diary.

The theme is a heavy adaptation of [XMin](https://themes.gohugo.io/hugo-xmin/).

Create a new hugo site, initialize git on it, and then add this repo as a submodule. Finally add the theme to your configuration:

```bash
$ hugo new site my-new-site
$ cd my-new-site
$ git init
$ git submodule add git@github.com:jsanz/mini-hugo.git themes/mini-hugo
$ echo 'theme = "mini-hugo"' >> config.toml
```

At that point you can start adding pages to the `content` folder and decide your website structure.

This site is meant to be used to the bare minimum with a config like, check the example site provided for reference.