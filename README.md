# Aura Beauty — Salon Kosmetyczny & SPA

Przykładowa strona wizytówkowa dla fikcyjnego salonu kosmetycznego i SPA **Aura Beauty** z Warszawy.

## Styl i design

- **Paleta**: ciepła biel (#faf7f5), pudrowy róż (#e8c9c1), nude (#d9b8a6), taupe (#8a7a70), miękkie złoto (#c2a878), ciemny tekst (#3a302b)
- **Fonty**: Cormorant Garamond (nagłówki, elegancki serif z italic) + Jost (body, nowoczesny sans-serif)
- **Styl**: elegancki minimalizm, duże whitespace, luksusowo i spokojnie

## Sekcje

1. **Nav** — stała nawigacja z CTA „Umów wizytę", efekt po scrollu
2. **Hero** — pełnoekranowe zdjęcie z gradientem, hasło, dwa CTA
3. **O salonie** — opis firmy, floating accent card z liczbami
4. **Zabiegi** — cennik podzielony na 3 kategorie (twarz / ciało / dłonie) z zakładkami
5. **Opinie** — 4 opinie klientek w stylu editorial
6. **Rezerwacja** — formularz (imię, telefon, zabieg, termin) z potwierdzeniem
7. **Kontakt** — adres, godziny, mapa OpenStreetMap iframe
8. **Footer** — nawigacja, kontakt, credit 100strona.pl

## Stack

- **Astro 5** — framework
- **Tailwind CSS 4** — style przez `@tailwindcss/vite`

## Komendy

```bash
npm install
npm run dev      # serwer developerski
npm run build    # build produkcyjny → dist/
npm run preview  # podgląd builda
```

## Hosting

Gotowe do wdrożenia na [Vercel](https://vercel.com) — wystarczy połączyć repozytorium.
