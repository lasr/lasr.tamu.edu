# LASR Site
[LASR Laboratory](http://lasr.tamu.edu/) public website.

# Development
The site is built with [Hugo](http://www.gohugo.io/), which renders the pages down to static HTML. Step one is to install Hugo.

For development, launch Hugo in watch mode, from the repository root:

```
hugo server -wv --bind "[your ip address]" -b "http://[your-ip]/"
```

Visit `http://[your-ip]/` in your browser. Pages should auto-reload when updated.

## Site Stylesheets

To develop stylesheets, first install [Sass](http://sass-lang.com/) node bindings with `npm i -g node-sass` and run `npm run watch-sass` from the repository root. Sass styles are located in `src/style/` and rendered to `static/css/`

## Notes
* Research section uses a content [list template](https://gohugo.io/templates/list/) to render research topics
