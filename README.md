# audiencekit.com

The AudienceKit marketing site, built with [Jekyll](https://jekyllrb.com) and
deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.
Developer documentation lives at [audiencekit.io](https://audiencekit.io), not here.

## Develop

```sh
mise install        # Ruby 3.3
bundle install
mise run serve      # http://localhost:4000
```

## Design

Colours, type, spacing and radii come from the AudienceKit design system and are
copied as CSS custom properties at the top of `assets/css/site.css`, in the
default preset (light and dark). The Hot Mess showcase uses the `hot_mess` preset,
scoped with `.theme-hot-mess`. Figtree is self-hosted from `assets/fonts/`.

| Path | What |
| --- | --- |
| `index.html` | The landing page |
| `_layouts/default.html` | Page shell (SEO tags, header, footer) |
| `_includes/` | Header and footer |
| `_config.yml` | Site URL, docs link, contact email |
| `CNAME` | `audiencekit.com` |
