<p align="center"><img src="https://raw.githubusercontent.com/go-embedded-ruby/brand/main/social/go-embedded-ruby.png" alt="go-embedded-ruby/go-embedded-ruby.github.io" width="720"></p>

# go-embedded-ruby.github.io

The organization's institutional landing page, served at
<https://go-embedded-ruby.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, phase cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-embedded-ruby/docs](https://github.com/go-embedded-ruby/docs), served at
<https://go-embedded-ruby.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
