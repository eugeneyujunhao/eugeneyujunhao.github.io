# eugeneyujunhao.github.io

Personal academic homepage of **Eugene Yu Jun Hao** — PhD student in Computer
Science at Peking University, research intern at Microsoft Research Asia.

Live at <https://eugeneyujunhao.github.io>.

## Stack

A static [Jekyll](https://jekyllrb.com/) site. The content lives in
`_pages/about.md`; the custom design layer is `assets/css/blueprint.css` plus
`_includes/head/custom.html`.

## Run locally

With Docker:

```bash
docker-compose up
# then open http://localhost:4000
```

Or with a local Ruby toolchain:

```bash
bundle install
bundle exec jekyll serve --livereload
```

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
template, a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes),
both MIT licensed. See `LICENSE`.
