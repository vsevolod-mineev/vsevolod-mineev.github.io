# sebastian-mineev.com

The source code of my resume, live at [sebastian-mineev.com](https://www.sebastian-mineev.com/).

You are probably here for one of three reasons:

1. **You are a recruiter doing due diligence.** Splendid. The polished version is on the website; this repo simply proves the YAML behind it is kept tidy.
2. **You are an engineer who wants a CV that is a website that is a Git repo.** Correct instinct. Fork away, the theme is MIT.
3. **You are me, several months from now, having forgotten how any of this works.** Hello, me. Read on.

## How this works

- A [Jekyll](https://jekyllrb.com/) static site served by GitHub Pages.
- The live site deploys from the **`gh-pages`** branch. `main` is a mirror. When they disagree, `gh-pages` is telling the truth.
- The entire resume is one file: [`_data/data.yml`](_data/data.yml). Everything else is plumbing.
- The favicon is a Space Invader. This is intentional and non-negotiable.

## Run it locally

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000 and admire.

## Change the resume

1. Edit `_data/data.yml`.
2. Push to `gh-pages`.
3. There is no step 3.

## Credits

Built on the [jekyll-cv](https://github.com/stavrospanakakis/jekyll-cv) theme by Stavros Panakakis ([MIT](LICENSE)). The career described within is entirely my own work.
