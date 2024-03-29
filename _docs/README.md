# Icarus Jekyll

Starter template for Jekyll projects for Github Pages.

## Installation

This website is made for Github Pages.

```
bundle install
```

## Usage

```
make optimize
make serve
```

## Technical information

### Jekyll

- [Documentation](https://jekyllrb.com)

### Jekyll plugins

See [_config.yml](_config.yml) and [Gemfile](Gemfile).

- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
- [jekyll-feed](https://github.com/jekyll/jekyll-feed)
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from)

### Front libraries

- [Bootstrap 4 beta](https://getbootstrap.com)

### Travis CI

A `.travis.yml` file is included.

## Architecture

### Data

All data files are in `_data` folder.

### Docs

All docs and source files are in the `_docs` folder.

### Template

Template are in `_layouts` and `_includes` folders.

### Assets

Assets (images, style, scripts) are in `_assets` folder.

### Posts

#### Process

- Posts (.md files) are to be saved in `_posts`, with the following format: `2011-12-31-new-years-eve-is-awesome.md`
- Posts should be tagged, for instance "Culture", "Tech", "Conference", ...
- Images that belong to a post go into images, prefixed with the posts's date (e.g. `2011-12-31-happy.png`) at 1200x803 size
- Drafts should end up in the folder _draft, without a prefixed date (e.g. `new-years-eve-is-awesome.md`)
- Use the _drafts folder to prepare your post before publishing
    ```bash
    jekyll serve --drafts
    ```

#### Reading time

Reading time module is included in the post template.

#### Schema

Schema is included in the post template.

## Makefile

Type `help` for all commands

- `serve`: Start a simple jekyll server.
- `drafts`: Start a simple jekyll server displaying drafts.
- `future`: Start a simple jekyll server displaying future posts.
- `optimize`: Optimize assets files (concat and minify css and js files).
