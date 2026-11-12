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

Pushes to `master` are built and published to GitHub Pages by `.github/workflows/jekyll.yml`.
