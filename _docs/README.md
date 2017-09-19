# Icarus Jekyll

Starter template for Jekyll projects for Github Pages.

## Installation

This website is made for Github Pages.

```ruby
bundle install
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

## Architecture

### Data

All data files are in `_data` folder.

### Docs

All docs and source files are in the `_docs` folder.

### Template

Template are in `_layouts` and `_includes` folders.

### Assets

Assets (images, style, scripts) are in `_assets` folder.

### Pages

Pages are in the `pages` folder.

### Posts

- Posts (.md files) are to be saved in `_posts`, with the following format: `2011-12-31-new-years-eve-is-awesome.md`
- Posts should be tagged, for instance "Culture", "Tech", "Conference", ...
- Images that belong to a post go into images, prefixed with the posts's date (e.g. `2011-12-31-happy.png`) at 1200x803 size
- Drafts should end up in the folder _draft, without a prefixed date (e.g. `new-years-eve-is-awesome.md`)
- Use the _drafts folder to prepare your post before publishing
    ```bash
    jekyll serve --drafts
    ```
