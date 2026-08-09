# Nahash's Descendants

Digital library for the analysis of Genesis: books, articles, maps, podcast, and resources.

Built with [Jekyll](https://jekyllrb.com/) and published with GitHub Pages. English counterpart of [Descendientes de Nahash](https://dskartes.github.io/DescendientesdeNahash/).

## Structure

```
├── _config.yml          # site configuration
├── _layouts/             # templates (home, default)
├── _includes/             # reusable nav and footer
├── assets/css/            # styles
├── index.md               # home page
├── books.md                 # full books
├── articles.md                # short articles
├── maps.md                      # maps
├── podcast.md                     # podcast episodes
├── resources.md                     # supporting resources
├── books/                             # book PDFs
└── podcast/                             # audio files
```

## Publishing

In **Settings → Pages**, choose the `main` branch as the source. GitHub builds the Jekyll site automatically — no manual build step needed.

The repository is named `NahashsDescendants`, so `_config.yml` has:

```yaml
baseurl: "/NahashsDescendants"
```

If you ever rename the repo, update that line too.
