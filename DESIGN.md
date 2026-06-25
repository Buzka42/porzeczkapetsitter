---
name: Petsitter Porzeczka
description: Luksusowa petsitterka w Warszawie — opieka z charakterem, bez kompromisów.
colors:
  currant: "#591937"
  currant-hover: "#7A2550"
  currant-tint: "#F2E8EE"
  parchment: "#F7F3EE"
  cream: "#EFE8DE"
  border: "#E2D9CE"
  ink: "#16100D"
  ink-secondary: "#5E5049"
  ink-tertiary: "#9B8C84"
  ink-on-dark: "#FAF7F3"
  currant-on-dark: "#D4A0B9"
typography:
  display:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "clamp(3.6rem, 8vw, 8rem)"
    fontWeight: 300
    lineHeight: 1.02
    letterSpacing: "normal"
  headline:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "clamp(2.6rem, 5vw, 4.2rem)"
    fontWeight: 300
    lineHeight: 1.08
  title:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "clamp(1.3rem, 2vw, 1.6rem)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "0.93rem"
    fontWeight: 300
    lineHeight: 1.9
  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "0.68rem"
    fontWeight: 500
    letterSpacing: "0.16em"
rounded:
  sharp: "0px"
  hairline: "3px"
  card: "4px"
  asymmetric-sm: "4px 24px 4px 24px"
  asymmetric-md: "4px 32px 4px 32px"
  asymmetric-lg: "6px 40px 6px 40px"
  pill: "100px"
spacing:
  xs: "0.45rem"
  sm: "1.4rem"
  md: "2.4rem"
  lg: "5rem"
  section: "140px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "#ffffff"
    rounded: "{rounded.pill}"
    padding: "0.8rem 1.8rem"
  button-primary-hover:
    backgroundColor: "{colors.currant}"
  button-ghost-light:
    backgroundColor: "transparent"
    textColor: "#ffffff"
    rounded: "{rounded.pill}"
    padding: "0.8rem 1.8rem"
  button-ghost-dark:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.8rem 1.8rem"
  nav-cta:
    backgroundColor: "transparent"
    textColor: "rgba(255,255,255,0.85)"
  nav-cta-scrolled:
    textColor: "{colors.currant}"
  booking-widget:
    backgroundColor: "#ffffff"
    rounded: "{rounded.asymmetric-sm}"
    padding: "44px 48px"
  booking-btn-next:
    backgroundColor: "{colors.currant}"
    textColor: "#ffffff"
    rounded: "{rounded.hairline}"
    padding: "0.72rem 1.6rem"
---

# Design System: Petsitter Porzeczka

## 1. Overview

**Creative North Star: "Prywatna Winiarnia"**

Petsitter Porzeczka prezentuje się jak miejsce ekskluzywne, ale nie zimne — wyrafinowane, familijne, z głębią odkrywaną stopniowo. Nie krzyczysz, nie błagasz o uwagę. Marka przemawia ciszą, proporcją i precyzyjnie dobranym detalem. Jak dobry rocznik: im dłużej go poznajesz, tym więcej warstw odkrywasz.

Wizualnie: ciepłe, głębokie, organiczne. Nie elegancja korporacyjna. Nie "professional pet care" z pastelowymi łapkami. Typografia czyta się zamiast skanować. Fotografia ma więcej wspólnego z magazynem niż z serwisem ogłoszeń. Każda sekcja to krok w głąb relacji — od pierwszego wrażenia (hero), przez zaufanie (o mnie, usługi), aż po decyzję (rezerwacja).

Ruch jest intencjonalny: editorial line-reveals na nagłówkach, stopniowe fade-iny, cursor jako przedłużenie brandingu. Strona "czyta się" jak rozdział, nie renderuje jak interfejs.

**Key Characteristics:**
- Głęboki porzeczkowy na pergaminie — bogaty, nie agresywny
- Cormorant Garamond jako głos marki — zmysłowy, wykształcony, niespiesznie
- Asymetryczne border-radii jako sygnatura rękodzieła, nie szablonu
- Whitespace jako luksus, nie pustka
- Realne zdjęcia i wideo — autentyczność ponad stockiem

## 2. Colors: Paleta Porzeczkowego Atrametu

Paleta polaryzacyjna: ciepła prawie-czarna ziemia kontra świetlany pergamin, z głębokim porzeczkowym jako jedynym akcentem chromatycznym. Nasycenie pojawia się rzadko — i dlatego zatrzymuje wzrok.

### Primary
- **Głęboki Porzeczkowy** (`#591937`): Jedyny saturowany kolor systemu. CTA, ceny usług, labele kategorii, podkreślenia nawigatora, separatory akcentowe. Musi być rzadki — jego siła pochodzi z nieobecności.
- **Porzeczka Hover** (`#7A2550`): Interaktywna wersja akcentu; hover states na przyciskach i bookingu.
- **Cień Porzeczki** (`#F2E8EE`): Tło za ikonami kontaktowymi, hover za listami serwisów — ciepły echo akcentu bez nasycenia.

### Neutral — Jasne
- **Stary Pergamin** (`#F7F3EE`): Główne tło serwisu. Z nutą archiwum — nie biały, nie papierowy krem z kartonu.
- **Krem Śmietankowy** (`#EFE8DE`): Tło sekcji usług i marquee. Nieznacznie cieplejszy — tworzy rytm głębokości bez cieni.
- **Lodowa Obwódka** (`#E2D9CE`): Separatory, obramowania siatki kalendarza, krawędzie input fields.

### Neutral — Ciemne
- **Ciemny Atrament** (`#16100D`): Główny tekst i tło sekcji obszaru i stopki. Prawie czarny z ciepłym podtonem.
- **Atrament Wtórny** (`#5E5049`): Tekst pomocniczy i opisy. Miększe od głównego atramenty — hierarchia bez szarości.
- **Atrament Popielny** (`#9B8C84`): Meta-informacje, placeholdery. Wyłącznie dla elementów dekoracyjnych; **nigdy na tekście wymagającym czytelności**.
- **Świt Pergaminu** (`#FAF7F3`): Tekst na ciemnym tle (sekcja obszaru, stopka). Cieplejszy niż biały.
- **Matowa Różana** (`#D4A0B9`): Elementy logo i dekoracje na ciemnym tle. Porzeczkowa muted — nie pastelowa.

**The One Voice Rule.** Głęboki Porzeczkowy (`#591937`) pojawia się na ≤10% powierzchni każdego ekranu. Jego rzadkość to jego wartość — gdy wzrok go spotyka, zatrzymuje się. Gdy jest wszędzie, jest niczym.

## 3. Typography

**Display Font:** Cormorant Garamond (weights: 300, 400, 500 + italic variants)
**Body Font:** Inter (weights: 300, 400, 500)

**Character:** Cormorant i Inter to para na osi kontrastu — jeden gotycko-literacki, zmysłowy, z przestrzenią między literami; drugi precyzyjny, techniczny, bezcieniowy. Razem mówią: "rozumiem i czuję". Cormorant niesie duszę marki; Inter dostarcza informację.

### Hierarchy
- **Display** (300, clamp(3.6rem, 8vw, 8rem), line-height 1.02): Hero headlines. Wyłącznie Cormorant weight 300. Litery "leżą" na stronie jak tytuł artykułu w Kinfolk. Jedno słowo-klucz zawsze w italic.
- **Headline** (300, clamp(2.6rem, 5vw, 4.2rem), line-height 1.08): Nagłówki sekcji. Ten sam spokój co Display, mniejsza skala.
- **Title** (400, clamp(1.3rem, 2vw, 1.6rem), line-height 1.55): Nazwy usług, pullquoty. Italic w cytatach jako gest emocjonalny, nie ozdobny.
- **Body** (300, 0.93rem, line-height 1.9): Opisy, treść akapitów, Inter. "Oddycha" jak long-read. Max ~65ch.
- **Label** (500, 0.68rem, letter-spacing 0.16em, uppercase, kolor: currant): Etykiety kategorii nad nagłówkami sekcji. Sygnatura sekcji.
- **UI/Nav** (400–500, 0.73–0.78rem, letter-spacing 0.08–0.1em, uppercase): Nawigacja, hinty, metadane. Inter.
- **Price Display** (300, 2rem, Cormorant, kolor: currant): Ceny usług. Range-price: 1.45rem.

**The Italic Touch Rule.** Kursywa Cormorant jest zarezerwowana dla jednego słowa-klucza per nagłówek. Nigdy całe zdanie w italics (poza pullquote). Italic to gest emocjonalny, nie styl tekstu.

**The Weight Floor Rule.** Inter nigdy poniżej 300. Cormorant nigdy poniżej 300. Cienkie fonty na kremowym tle tworzą kontrast poniżej 4.5:1 — system nie wchodzi w tę pułapkę.

## 4. Elevation

System jest **płaski z jednym strategicznym wyjątkiem**. Głębię tworzy kolor i spacing — nie cienie.

Jedyny oficjalny shadow: booking widget — `box-shadow: 0 4px 40px rgba(22,16,13,.07)`. Ledwo widoczna mgła, nie unosi widgetu — delikatnie oddziela go od pergaminu.

Strukturalna głębia pochodzi z:
- Naprzemiennych teł sekcji (pergamin → krem → ciemny atrament)
- Granic `1px solid var(--border)` na listach i kalendarzach
- Hover pseudo-elementów (tło za row pojawia się na najechaniu)

**The Shadow Exception Rule.** Cień jest dozwolony wyłącznie na booking widget. Każdy inny element wymagający wyróżnienia musi używać kontrastu kolorystycznego lub obramowania — nigdy `box-shadow` jako pierwszego wyboru.

## 5. Components

### Buttons

Dwa reżimy: główne CTA stronowe (pill) i wewnętrzne widgetowe (ostre).

**Główne CTA:**
- **Shape:** `border-radius: 100px` (pełne pill)
- **Primary (Ink):** `background: #16100D`, biały tekst, `padding: 0.8rem 1.8rem`, SVG arrow. Hover: `background: #591937` + `translateY(-2px)` + `box-shadow: 0 10px 28px rgba(89,25,55,.3)`.
- **Ghost Light:** `border: 1.5px solid rgba(255,255,255,.45)`, biały tekst — na ciemnym hero.
- **Ghost Dark:** `border: 1.5px solid #16100D`, ciemny tekst — na jasnych sekcjach.
- **Nav CTA:** Bez tła, bez radius — `border-bottom: 1.5px solid`. Biały na hero, porzeczkowy po scroll.

**Widget CTA:**
- **Shape:** `border-radius: 3px` (prawie ostre)
- **Next:** `background: #591937`, biały tekst, hover `#7A2550` + `translateY(-1px)`.
- **Back:** brak tła, `color: var(--ink3)`, hover: `color: var(--ink)`.

**The Pill Quarantine Rule.** `border-radius: 100px` jest dozwolony wyłącznie na `.btn`. Żaden tag, badge, label, element widgetu nie może używać pill. Asymetria lub ostre narożniki — to znaki systemu.

### Cards / Containers

Projekt **nie używa kart jako modułów layoutu** — decyzja fundamentalna. Informacja prezentowana jest w rows i sekcjach.

Jedyny kontener kartowy: booking widget.
- **Corner Style:** `border-radius: 4px 24px 4px 24px` (asymetryczny)
- **Background:** biały na pergaminowym tle
- **Border:** `1px solid var(--border)`
- **Shadow:** `0 4px 40px rgba(22,16,13,.07)`
- **Padding:** `44px 48px` desktop

Image frame o mnie: `border-radius: 6px 40px 6px 40px`.
Mapa frame: `border-radius: 4px 32px 4px 32px`.

**The Human Hand Rule.** Asymetryczne radii (4/24, 4/32, 6/40) to sygnatura marki — wyglądają jak świadomy wybór, nie skopiowany szablon. Narożniki są albo pill, albo asymetryczne, albo 0.

### Service Rows

Grid: `64px | 1fr | max-content | 44px`.
- Separator: `1px solid var(--border)` góra i dół.
- Hover: pseudo-element `::after` reveals jasne tło; numer i tytuł → currant; strzałka obraca się 45° i wypełnia currantem.
- Cena: Cormorant 2rem/300, currant. Range ceny: 1.45rem.

### Inputs / Fields

Booking widget:
- `border: 1.5px solid var(--border)`, `border-radius: 4px`, biały bg.
- Focus: `border-color: #591937`.
- Label: Inter 500, 0.65rem, uppercase, `letter-spacing: 0.1em`, `color: var(--ink3)`.

### Navigation

Fixed, dwa stany:
1. **Na hero:** logo i linki białe/rgba(255,255,255,.75). CTA: biały underline.
2. **Po scroll:** `background: rgba(247,243,238,.93)`, backdrop-filter blur, linki `var(--ink2)`. CTA: currant underline.

Hover linków: `scaleX(0→1)` cienka porzeczkowa linia pod linkiem.

### Calendar (Booking Widget)

Europejski (Pn–Nd start), polska lokalizacja.
- Grid 7 kolumn, dni `aspect-ratio: 1`, `border-radius: 50%`.
- Available hover: `background: var(--currant-tint)`, tekst currant.
- Selected: `background: var(--currant)`, biały tekst.
- Range-start: `border-radius: 50% 0 0 50%`. Range-end: `border-radius: 0 50% 50% 0`. In-range: `border-radius: 0`, currant-tint bg.
- Unavailable (przeszłość, niedziele): `color: var(--border)`.

## 6. Do's and Don'ts

### Do:
- **Do** używaj whitespace jako designu — `padding: 140px 0` per sekcja mówi: "to nie sklep, to doświadczenie".
- **Do** stosuj Cormorant italic wyłącznie na jednym słowie-kluczu per nagłówek — gest emocjonalny, nie styl.
- **Do** utrzymuj Głęboki Porzeczkowy jako jedyny saturowany kolor — rzadkość to jego moc.
- **Do** używaj asymetrycznych border-radii (4/24, 4/32, 6/40) jako sygnatury rzemiosła.
- **Do** animuj nagłówki sekcji line-reveal (`translateY(102%)→0`) — editorial pacing.
- **Do** kontrastuj sekcje naprzemiennym tłem (pergamin / krem / ciemny atrament).
- **Do** stosuj cursor customowy — porzeczkowy na jasnym, biały na ciemnym hero.
- **Do** sprawdzaj kontrast body text — Inter 300 na kremowym to pułapka; sprawdź 4.5:1.

### Don't:
- **Don't** używaj kolorowych ilustracji, bajkowych grafik, ikon łap — kitsch pet industry to główna anty-referencja.
- **Don't** stosuj pill (`border-radius: 100px`) poza `.btn` — tagi, labele, elementy widgetów: zawsze ostre lub asymetryczne.
- **Don't** generuj "generic AI slop" — uniformowe karty, `<input type="date">`, gradient overlaye, pastelowe boxy.
- **Don't** dodawaj drugiego akcentu chromatycznego — Porzeczkowy jest samotny z wyboru.
- **Don't** używaj stockowych zdjęć zwierząt — tylko realne fotografie podopiecznych Magdy.
- **Don't** skaluj nagłówków display powyżej `8rem` — strona mówi, nie krzyczy.
- **Don't** stosuj uniform border-radius (np. `8px` na wszystkim) — to znak szablonu, nie projektu.
- **Don't** dodawaj elementów "żeby były" — każdy komponent musi pracować na zaufanie właściciela pupila.
