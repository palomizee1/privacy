# Privacy Policy — Finora Budget · Vitals Flow · Smart Utility Hub

**Live page: https://palomizee1.github.io/privacy/**

Available in English, Español, Deutsch, Français and Português (Brasil) via the language
selector. A specific language can be linked directly — App Store Connect accepts a
privacy-policy URL per locale:

| Locale | URL |
|---|---|
| English | https://palomizee1.github.io/privacy/?lang=en |
| Español | https://palomizee1.github.io/privacy/?lang=es |
| Deutsch | https://palomizee1.github.io/privacy/?lang=de |
| Français | https://palomizee1.github.io/privacy/?lang=fr |
| Português (BR) | https://palomizee1.github.io/privacy/?lang=pt-BR |

Without an explicit `?lang=`, the page follows the visitor's browser language and falls back
to English.

## Editing

`index.html` is **generated** — don't hand-edit it, or the next build overwrites your change.
The source is the `PRIVACY_POLICY*.md` files in the PersonalSuite repository:

```
python3 Scripts/build_pages.py privacy <path-to-this-repo>
```

The build **redacts personal data**: the developer name and contact email are replaced with
`[Developer name]` and `[contact email]`, and it refuses to write a file that still contains
them. This repo is public and its history is permanent — those two fields are filled in on
the live page by hand, never committed here.

The English text is authoritative; the translations carry a precedence clause saying so.
