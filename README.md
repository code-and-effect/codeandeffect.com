[![Netlify Status](https://api.netlify.com/api/v1/badges/20a9b92a-ac5f-459e-8ec6-1be39f13f3a2/deploy-status)](https://app.netlify.com/sites/codeandeffect/deploys)

# codeandeffect.com

This the public website for Code and Effect. It used [effective_jekyll](https://github.com/code-and-effect/effective_jekyll) as the starter template and is hosted by [Netlify](https://www.netlify.com).


## Installed Plugins

- [jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)
- [jekyll-gzip](https://github.com/philnash/jekyll-gzip)
- [jekyll-menus](https://github.com/forestryio/jekyll-menus)
- [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from)
- [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)


## Notes re: Bootstrap 4.4.1

- CDNs for the JS (Jquery, Bootstrap, and Popper) are included at the bottom of `_includes/default.html`
- Customize Bootstrap by editing `_sass/bootstrap-4.4.1/_variables.scss`
- Comment out unused Bootstrap components @included in `_sass/bootstrap-4.4.1/bootstrap.scss`
- Override compiled Bootstrap components in `_sass/componenents/*`


## Notes re: Editor

- Sublime Text: add `_site` and `.jekyll-cache` to your `folder_exclude_patterns` via Preferences --> Settings
- VS.Code: I dunno something similar though :)


## New Site Setup

1. Clone this repo
2. `bundle install`
3. `bundle exec jekyll serve`


## data vs collections

- If it gets it's own page, it's a collection
- If it only gets looped through somewhere else, it's data


## Icons

This website uses a combination of the following icon sets:

- https://github.com/feathericons/feather
- https://github.com/tabler/tabler-icons
- https://github.com/lucide-icons/lucide


## License

Copyright [Code and Effect Inc.](http://www.codeandeffect.com/)


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new pull request
