# BRIEF v2 — Landing „Skin Solutions" (LUXE, wzorowany na Estetic Point)

## Cel
Druga wersja landingu kliniki kosmetologii/medycyny estetycznej **Skin Solutions** (Mokotów, Warszawa) — utrzymana w **luksusowym, „celebryckim" stylu** wzorowanym na stronie-przykładzie estetic-point.pl/green-sea-peel. Cel konwersyjny ten sam: rezerwacja Booksy + telefon. Ma robić wrażenie ekskluzywnej kliniki premium („chcę tam pójść", „to miejsce dla mnie"). Grupa docelowa: kobiety 25–55.

Treść: WYŁĄCZNIE z `_brief/CONTENT.md` (te same realne dane: Karolina Wrąbel, Aleksandra Sadza, 5 kategorii oferty, cennik „od", NAP, Booksy). Nie zmyślać.

## Paleta (DECYZJA użytkownika — LUXE czerń+złoto+biel + zieleń marki jako akcent)
W `:root`:
- `--ink: #14130F` i `--black: #000000` — głębokie tła sekcji (luksusowa czerń/grafit), bazowy „dramatyczny" klimat.
- `--gold: #D2AC67` — **szampańskie złoto = kolor sygnaturowy** (akcenty, cienkie linie/ramki, przyciski, ikony, liczby, gwiazdki, podkreślenia, hover). To kolor wzoru — ma być wyraźnie obecny.
- `--gold-soft: #E4C98C` / `--gold-deep: #B7935440` (rozjaśnienie/cień złota).
- `--white: #FFFFFF`, `--cream: #F3EEE6` — jasne sekcje „oddechu" (kontrast do ciemnych).
- `--green: #3a5d49` (+ `--green-900:#243A2D`) — **zieleń marki jako bogaty drugorzędny akcent** (np. naprzemienne ciemne sekcje, detale botaniczne, tła wybranych bloków). Łączy luksus wzoru z tożsamością Skin Solutions.
- Tekst: na ciemnym → `#F3EEE6`/biel; na jasnym → `#1A1814`/grafit. **Kontrast WCAG AA bezwzględnie** (złoto #D2AC67 na czerni = OK dla dużego tekstu/akcentów; dla drobnego tekstu na ciemnym używaj kremu/bieli, NIE złota).
- Wrażenie docelowe: czerń + złoto + biel z akcentem zieleni = elegancja, prestiż, spokój.

## Typografia
Elegancki, „drogi" duet: nagłówki serif/display (np. **Cormorant Garamond** lub **Playfair Display** — duże, cienkie, z charakterem), tekst lekki sans (**Jost**/**Inter**/**Manrope**). Wersaliki z mocnym letter-spacingiem w eyebrow/nadtytułach (złote). `display=swap` + preconnect.

## MOCNE CECHY WZORU do zastosowania (struktura sekcji — kolejność)
1. **Header** sticky, ciemny, ze złotym akcentem; logo „Skin Solutions" (serif), nav, CTA „Umów wizytę" (złoty przycisk).
2. **Hero dramatyczny** (ciemne tło/zdjęcie + overlay grafit-złoto): duży serif nagłówek + podtytuł, 2 CTA (Booksy złoty + „Poznaj zabiegi" outline), oraz **rząd odznak-statów/USP** (jak wzór: „1000+ zadowolonych klientek", „Autorskie terapie łączone", „Holistyczne podejście", „Topowe technologie"). Liczby/odznaki ze złotym akcentem.
3. **Pasek korzyści** — 4 kafelki z ikonami liniowymi (złote), np.: „Naturalna odnowa skóry", „Indywidualny plan terapii", „Topowe sprzęty i kosmetyki", „Doświadczony, szkolący się zespół".
4. **Oferta — 5 kategorii** (Konsultacje, Terapie twarzy, Terapie ciała, Depilacja laserowa, Medycyna estetyczna): ciemne luksusowe karty ze złotą ramką/akcentem na hover, ikony, krótkie opisy + „od X zł".
5. **„Jak wygląda wizyta" — TIMELINE 3 kroki** (mocna cecha wzoru): „Konsultacja i diagnostyka skóry" → „Spersonalizowany plan i zabieg" → „Pielęgnacja domowa i zalecenia". Numerowane, ze złotą linią/krokami.
6. **„Co nas wyróżnia" / Autorskie terapie łączone** — sygnaturowa sekcja + **animowany licznik 1000+** klientek (złoty). Cytat o autorskich terapiach łączonych.
7. **Technologie premium** — grid „dowodów": Dermapen 4.0, Secret RF 2.0, Venus Legacy, Endermologia ICOONE Laser, platforma laserowa ZYE. Eleganckie kafelki/odznaki ze złotem.
8. **Cytat założycielki** (Karolina Wrąbel) — ciemna, kameralna sekcja z portretem (placeholder) + dużymi złotymi cudzysłowami; podpis. Wspomnij Aleksandrę Sadzę (zespół).
9. **Cennik orientacyjny „od"** — czytelna, elegancka lista/karty wybranych pozycji z CONTENT.md + CTA do rezerwacji/pełnego cennika.
10. **Opinie klientek** — karty z **złotymi gwiazdkami** + odznaka Google/Booksy (oznacz jako przykładowe, bo brak realnych cytatów).
11. **„Zobacz nas / Obserwuj"** — Instagram @skinsolutions.clinic (galeria kafelków, link). Odpowiednik sekcji „w praktyce".
12. **FAQ — AKORDEON** (mocna cecha wzoru): 5–6 pytań ugruntowanych w danych/bezpiecznych: „Jak umówić wizytę?" (Booksy/telefon), „Czy pierwsza wizyta to konsultacja?" (konsultacja od 150 zł, bezpłatna przy zabiegu tego samego dnia — z CONTENT), „Czym są autorskie terapie łączone?", „Jak przygotować się do wizyty?" (ogólnie, bezpiecznie), „Gdzie się znajdujecie?" (Cybernetyki 6/U2, Mokotów), „Jak działają pakiety zabiegów?" (z cennika). Akordeon dostępny (`button[aria-expanded]` + `aria-controls`). YMYL: ton ostrożny, bez gwarancji efektów medycznych.
13. **Kontakt + mapa + godziny + formularz** (mailto fallback) — ciemna lub kremowa sekcja, mapa Google iframe na adres.
14. **Końcowe CTA band** — mocne, złoto-na-czerni: „Zarezerwuj wizytę i zadbaj o swoją skórę".
15. **Footer** ciemny — NAP, godziny, social, linki prawne, ©.
+ **Pływające/sticky CTA „Umów wizytę"** na mobile (powtarzane CTA — cecha wzoru).

## Ograniczenia techniczne (TWARDE — jak v1)
- **Statyczny**: `index.html` (root) + `assets/css/styles.css` + `assets/js/main.js` + `assets/img/`. Bez frameworka/build-stepu.
- **Ścieżki WZGLĘDNE** (`assets/...`). Hosting GitHub Pages **projektowy pod `https://pflgroup.github.io/skinsolutions-lp-v2/`** — to ważne dla canonical/OG/sitemap (URL bazowy = ten).
- Responsywne mobile-first (360→1440+), hamburger nav. Dostępność: 1×h1, semantyka, alt, aria, `:focus-visible`, kontrast AA, `prefers-reduced-motion` wyłącza animacje, akordeon FAQ dostępny z klawiatury.
- Obrazy stockowe Unsplash (hotlink CDN `?w=...&q=80&auto=format&fit=crop`), tematyka skincare/spa/luxury/botanika — ale w ciemnej, eleganckiej tonacji. Każdy kontener obrazu ma w CSS gradient w barwach (czerń/złoto/zieleń) POD obrazem (odporność na zepsute zdjęcie). Adnotacja w komentarzu HTML + stopce „zdjęcia poglądowe (stock) — do podmiany".
- `lang="pl"`, UTF-8, poprawna diakrytyka.

## Klasy-haki dla JS (Design zostawia, Build podpina) — jak v1 + akordeon:
`.js-nav-toggle` + `#primary-nav` (`.is-open`); `[data-reveal]` (+`.is-visible`); `.counter[data-target]`; `#year`; `#contact-form` (+pola `#cf-*`); `.site-header` (`.is-scrolled`); **FAQ: `.faq__q` = `button[aria-expanded][aria-controls]`, panel `.faq__a` z `id`**; **sticky mobile CTA: `.mobile-cta` (pokazywany po przewinięciu hero)**.

## OBOWIĄZKOWE — Branding PFL + zabezpieczenie (każdy landing PFL)
### Stopka PFL (dokładny tekst)
W stopce osobna linia copyright:
`© <rok> Copyright by PFL Group. Wszelkie prawa zastrzeżone.`
— gdzie **„PFL Group" jest linkiem** do `https://www.pflgroup.pl` (`target="_blank" rel="noopener"`), a `<rok>` to `<span id="year">2026</span>` (JS ustawi bieżący). To DODATKOWA linia obok „© Skin Solutions" (klient) — można połączyć w jednej stopce: „© 2026 Skin Solutions · Realizacja: [PFL Group](pflgroup.pl) — Wszelkie prawa zastrzeżone." LUB dwie linie. Najważniejsze: tekst „© <rok> Copyright by PFL Group. Wszelkie prawa zastrzeżone." z linkiem na pflgroup.pl MUSI być.

### Zabezpieczenie anty-kopiowanie (Design przygotowuje CSS, Build implementuje JS `protect()`)
- CSS: `body{user-select:none}` + `::selection{background:transparent}`; WYJĄTEK `input,textarea,[contenteditable]{user-select:text}`. Obrazy: `-webkit-user-drag:none`.
- JS (kolejny agent, ale uwzględnij w strukturze): blokada `contextmenu`, `copy`/`cut` (poza polami), `dragstart` obrazów, skrótów `F12`/`Ctrl+Shift+I/J/C`/`Ctrl+U`/`Ctrl+S`; **anti-rehost**: allowlist hostów (`pflgroup.github.io`, `localhost`, `127.0.0.1`) → poza listą redirect na `https://www.pflgroup.pl`.
- Ochrona NIE może łamać CTA/nav/formularza ani dostępności. To deterrenty.

## Czego NIE robić
Nie zmyślać cen/nazwisk/liczby lat/certyfikatów. Nie kalkować 1:1 Estetic Point (inspiracja strukturą+kolorami, ale własna realizacja Skin Solutions). Nie ścieżki absolutne. Bez realnego ID analytics. YMYL — bez obietnic medycznych.

## Sukces
Wygląda jak ekskluzywna klinika premium (czerń+złoto+biel z zielenią), ma mocne cechy wzoru (hero-staty, timeline, FAQ, powtarzane CTA), jest szybka, responsywna, dostępna, z poprawnym SEO. Kobieta z grupy docelowej: „to miejsce z najwyższej półki — chcę się umówić".
