# mielina-site

Mielina's website, served by GitHub Pages at https://alexraducanu97.github.io/mielina-site/ (Settings › Pages: Deploy from a branch, `main`, `/ (root)`). The store listings link to it.

| Page | Address | Store field |
|------|---------|-------------|
| Privacy policy | https://alexraducanu97.github.io/mielina-site/privacy.html | Google Play's privacy policy, App Store Connect's Privacy Policy URL (English) |
| Politica de confidențialitate | https://alexraducanu97.github.io/mielina-site/privacy.ro.html | App Store Connect's Privacy Policy URL (Romanian) |
| Support | https://alexraducanu97.github.io/mielina-site/support.html | App Store Connect's Support URL (English), Google Play's website |
| Asistență | https://alexraducanu97.github.io/mielina-site/support.ro.html | App Store Connect's Support URL (Romanian) |

## The privacy policy

`privacy.md` and `privacy.ro.md` are byte-for-byte copies of `docs/privacy.md` and `docs/privacy.ro.md` in the app's repository, which the app writes from its own text (`WRITE_PRIVACY_DOCS=1 flutter test test/features/settings/privacy_test.dart`). Never edit them here: change the app's text, write the docs again there, and copy both files here on the day that change is merged. Their language and the link to the other language come from `_config.yml`, so the files need no front matter. To check the copies match, from the app's checkout:

```bash
for f in privacy.md privacy.ro.md; do
  curl -fsS "https://raw.githubusercontent.com/AlexRaducanu97/mielina-site/main/$f" | diff - "docs/$f" && echo "$f matches"
done
```

## The rest

- `index.md`, `support.md`, `support.ro.md` are written here. They name the app's own menus and buttons, so a change to Settings › About Mielina › Report a problem or Settings › Backup changes them too.
- `_layouts/default.html` and `assets/site.css`: one column, light and dark, no scripts, nothing loaded from another site, no cookies and no analytics.
- GitHub Pages builds the Markdown with its default plugins (front matter optional, titles from the first heading). Nothing else is installed.
