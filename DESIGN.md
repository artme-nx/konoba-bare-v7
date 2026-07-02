# DESIGN.md — Konoba Bare v7 (finalna, na bazi klijentove v5)

register: brand
status: KLIJENT ODABRAO v5 — dizajn i tekst su ZAKLJUČANI. v7 = v5 + nevidljive gate nadogradnje (S3 fontovi, SEO/schema, a11y, GDPR karta, lokalne slike). NE mijenjati vizual ni copy.

## Paleta (izvedena iz otoka Prvića — zaključana iz v5)
- `--bg-parchment #F4EEE1` — vapno i kamen šepurinskih kuća
- `--bg-alt #EBE3D2` — sjena u kaleti
- `--terra #B5784A` — crijep i zemlja
- `--olive #5B6B3A` — maslina (primarni akcent, CTA)
- `--sea #3E6374` — kanal pred otokom
- `--charcoal #2C2C2C` — tekst / footer
- `--stone #8C7F72`, `--sage #A3B18A` — potporni

## Fontovi (zaključano iz v5; self-host woff2, S3)
- Display: Cormorant Garamond (400/500/600 + italic) — heritage elegancija otoka
- Body: DM Sans (300/400/500)

## Hero (zaključano)
Fullbleed drone fotografija Prvić Šepurina + zoom-OUT na scroll (scale 1.35→1.0, scrub). Scroll indikator "Polako".

## Potpisne interakcije (zaključano iz v5)
1. Zoom-out hero na scroll (scrub 1) — 1 scrub
2. Ken Burns na story slici (scrub 1) — 2 scruba UKUPNO (u budžetu 6/3)
3. `.reveal` fade+26px na sekcijama (ne-scrub)
4. `.t-reveal` blur-to-focus na story tekstu (ne-scrub)
5. Sepia hover galerija + sensory microcopy na jelima

## Dekorativni potpis (zaključano)
SVG line-art divideri: barka/jedro + dvije masline; grain overlay 5%. NE koristiti na drugim klijentima.

## Tvrda pravila koja se ne smiju pregaziti
- Keyless mapa (S2) — sada iza GDPR facade (klik-za-učitavanje)
- Self-host fontovi (S3), bez runtime Google Fonts
- Bez tajni u kodu (S1)
- Copy je klijentov FINAL — ne prepisivati
- SEO/schema: Restaurant JSON-LD sa stvarnim podacima (tel +385 22 448 094, Prvić Šepurine)

## TODO[klijent]
- Potvrditi radno vrijeme (sezonski 12:00–23:00 preuzeto iz v5)
