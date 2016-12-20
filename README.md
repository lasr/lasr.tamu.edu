# LASR Site
[LASR Laboratory](http://lasr.tamu.edu/) public website.

## Updating
How to update the site:

### Adding News Items

### Adding a Publication

### Adding a New Lab Member

### When Someone Leaves LASR

### Adding Research Topics

#### A Note About Research Categories
When adding a research topic, the `research_category` parameter in the file's front matter defines how the content is grouped on the [Research](https://lasr.tamu.edu/research/) page. Setting to a never-before-seen research category will simply create that new category.

## Deploying the Site


## Development
The site is built with [Hugo](http://www.gohugo.io/), which renders the pages down to static HTML. Step one is to install Hugo.

For development, launch Hugo in watch mode, from the repository root:

```
hugo server -wv --bind "[your ip address]" -b "http://[your-ip]/"
```

Visit `http://[your-ip]:1313/` in your browser. Pages should auto-reload when updated.

### Site Stylesheets

To develop stylesheets, first install [Sass](http://sass-lang.com/) node bindings with `npm i -g node-sass` and run `npm run watch-sass` from the repository root. Sass styles are located in `src/style/` and rendered to `static/css/`

## Notes
* Research section uses a content [list template](https://gohugo.io/templates/list/) to render research topics

## TODO
- [x] Research topic sections
- [ ] Proper News display on home page
- [ ] Abstracts for publications + display in site
- [ ] BibTex output for publications
