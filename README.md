# AudienceKit website

Jekyll source for [audiencekit.com](https://audiencekit.com/).

The website presents AudienceKit and its Focus (Admin / Platform), Velvet
(Venues), and Backstage (Performers / People) apps. Featured audience preview
content lives in `_data/featured_audiences.yml`.

## Local development

With Ruby 3.3 or newer:

```sh
bundle install
bundle exec jekyll serve
```

Build with `JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter`.
Pushing to `main` publishes through the existing GitHub Pages workflow.
