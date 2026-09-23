# Lanova Fit — prezentacja produktu (PL)

Prezentacja produktu Lanova Fit dla inwestorów, po polsku, wrzesień 2026.

- **[Lanova_Fit_prezentacja_PL.pdf](Lanova_Fit_prezentacja_PL.pdf)** — 12 slajdów 16:9, wersja do wysłania i do druku.
- `deck.html` — źródło prezentacji.
- `zrzuty/` — 18 zrzutów ekranu z aplikacji w wersji polskiej, bez pasków systemowych telefonu.
- `fonts/` — Archivo (SIL Open Font License), krój użyty w prezentacji.

Miejsca oznaczone `[do uzupełnienia]` czekają na dane, których nie da się wziąć
z produktu: wielkość rynku, cennik subskrypcji, termin wydania na iOS, zespół
oraz parametry rundy.

## Jak zbudować PDF ponownie

Po edycji `deck.html`:

```
chrome --headless --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=Lanova_Fit_prezentacja_PL.pdf deck.html
```

Rozmiar strony (338 × 190 mm, czyli 16:9) jest ustawiony w `@page` wewnątrz
`deck.html`, więc nie trzeba podawać go w wierszu poleceń.

Kod aplikacji i strony internetowej jest w osobnym repozytorium.
