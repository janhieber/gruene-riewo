# Website Ortsverband

Jekyll-Website auf Basis von [gruene-theme](https://github.com/janhieber/jekyll-theme-gruene).

## Lokal starten

```sh
bundle install
bundle exec jekyll serve
```

Dann http://localhost:4000 öffnen.

## Inhalte

- News: `_posts/JJJJ-MM-TT-titel.md`
- Termine: `_termine/JJJJ-MM-TT-titel.md` (mit `datum: "JJJJ-MM-TT HH:MM"`)
- Menü: `_data/navigation.yml`
- Einstellungen: `_config.yml`

Die Seite sollte regelmäßig neu gebaut werden, damit kommende Termine aktuell bleiben.

## Lizenz

Code unter MIT, eigene Texte unter CC BY 4.0 – siehe [LICENSE](LICENSE).
Logo, Schriften und Fotos sind ausgenommen.
