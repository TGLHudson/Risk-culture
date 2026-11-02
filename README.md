# Hudson Risk Culture (HRC) website

Source for [hudsonriskculture.com](https://hudsonriskculture.com): risk culture, from T. G. L. Hudson (Hudson Global Consulting).

Work on this site happens in Claude Code cloud sessions. The working brief, with rules and open decisions, is in [CLAUDE.md](CLAUDE.md).

## How the site is built

The site uses [Jekyll](https://jekyllrb.com/), which GitHub Pages builds directly from this repository with no separate build step. Pages are plain Markdown files with a short header; the output is static HTML and CSS with no JavaScript.

| Path | What it holds |
|---|---|
| `_config.yml` | Site title, description, and the main navigation (`nav`) |
| `_layouts/default.html` | The page template |
| `_includes/` | Header, footer and the home-page hero |
| `assets/css/site.css` | All styling, following `STYLE.md` |
| `assets/fonts/` | Montserrat and Source Sans 3, self-hosted (SIL Open Font Licence, copies included) |
| `STYLE.md` | The Hudson family style guide: palette, type and components shared with hudsonglobalconsulting.com and the book's site |
| `index.md`, `approach.md`, `consulting.md`, `tools.md`, `publications.md`, `culture-ladder.md`, `about.md`, `contact.md` | The pages |

Content still to be supplied or cleared for publication is marked in the pages as `<p class="placeholder">…</p>` and shows on the site in a yellow box headed "Placeholder". Search for `placeholder` to find them all. None should remain at go-live.

### Preview locally (optional)

```bash
bundle install
```

```bash
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Going live (not yet done)

1. In the repository's **Settings → Pages**, set the source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
2. In the same place, enter the custom domain `hudsonriskculture.com` and, once the certificate is issued, tick **Enforce HTTPS**.
3. At the domain registrar, set these DNS records (GitHub Pages' published addresses):

| Type | Name | Value |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |
| CNAME | `www` | `tglhudson.github.io` |

Remove any other A, AAAA or CNAME records for `@` and `www`. Check the current addresses against GitHub's documentation, *Managing a custom domain for your GitHub Pages site*, before setting them.
