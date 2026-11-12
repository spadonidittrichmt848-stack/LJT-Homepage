# LJT-Homepage

Personal academic homepage of **Junteng Liu**, first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology.

The site is built with Jekyll using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which is a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Site content

| Path | Content |
| --- | --- |
| `_pages/about.md` | Front page: biography, research interests, education, research experience, publications, honors and awards, and contact information |
| `_pages/publications.html` | Publications listing page |
| `_publications/` | One Markdown file per publication |
| `_config.yml` | Site-wide settings and the author profile shown in the sidebar |
| `_data/authors.yml` | Author metadata |
| `_data/navigation.yml` | Header navigation |

## Deployment

Pushes to `master` are built by `.github/workflows/jekyll.yml`. The workflow uploads the built site as a
GitHub Pages artifact and also publishes it to the `gh-pages` branch.

GitHub Pages has to be enabled once for this repository (Settings → Pages) before the site is served at
<https://spadonidittrichmt848-stack.github.io/LJT-Homepage/>. Either publishing source works:

- **Deploy from a branch** — `gh-pages` / `/ (root)`; the workflow keeps this branch up to date.
- **GitHub Actions** — the workflow deploys the built artifact directly.

To preview locally: `bundle install` and then `bundle exec jekyll serve`.
