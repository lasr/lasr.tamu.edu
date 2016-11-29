# LASR Site
[LASR Laboratory](http://lasr.tamu.edu/) public website.

# Development
The site is built with [Hugo](http://www.gohugo.io/), which renders the pages down to static HTML. Step one is to install Hugo.

For development, launch Hugo in watch mode, from the repository root:

```
hugo server -wv --bind "[your ip address]" -b "http://[your-ip]/"
```

Visit `http://[your-ip]/` in your browser. Pages should auto-reload when updated.
