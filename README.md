# MemeForge 🎭

Webová aplikácia na tvorbu memov z obrázkov aj videí — priamo v prehliadači, bez inštalácie.

## O projekte

MemeForge je klientská webová aplikácia vytvorená ako súčasť predmetu **B-MSAP**. Umožňuje používateľom vytvárať memy z obrázkov aj videí, aplikovať filtre a efekty, pridávať nálepky a generovať vtipné texty pomocou AI.

## Funkcie

### 🖼 Obrázok
- **Nahrávanie** — Drag & Drop alebo výber súboru (JPG, PNG, WebP)
- **Text** — horný a dolný text s nastavením veľkosti, farby, fontu a obrysu
- **9 filtrov** — Normal, B&W, Warm, Cold, Vintage, Invert, Faded, Dramatic, Sunset
- **Pixelizácia** — 8-bit retro efekt exportovateľný do PNG
- **Vignette** — tmavé rohy pre dramatický vzhľad
- **Nálepky** — 20 emoji nálepiek kliknutím na obrázok
- **Rotácia a flip** horizontálne
- **Export** — stiahnutie v plnom rozlíšení ako PNG

### 🎬 Video / GIF
- **Nahrávanie videa** — Drag & Drop (MP4, WebM, MOV)
- **Text na video** — horný a dolný text s live náhľadom
- **6 video filtrov** — Normal, B&W, Sepia, Invert, Hue, Vivid
- **Jas a kontrast** — real-time úprava
- **Nálepky na video**
- **Zachytenie frame** — export aktuálneho snímku ako PNG
- **GIF export** — nastaviteľný začiatok, dĺžka a kvalita

### 🤖 AI Meme Generátor (obraz aj video)
- Generovanie vtipných textov podľa témy a nálady
- 5 nálad: Vtipný, Dark humor, Wholesome, Absurdný, Slovenský
- 80+ lokálnych šablón — funguje bez internetu aj bez API
- Jedným klikom vloží text do editora

## Použité technológie

- HTML5 / CSS3 / JavaScript
- Canvas API (kreslenie, filtre, pixelizácia, vignette, export)
- FileReader API (načítanie súborov)
- Web Video API (prehrávanie a spracovanie videa)
- gif.js (GIF export klient-side)
- Čisto frontend — žiadny backend, žiadny server

## Ako používať

1. Otvor aplikáciu v prehliadači
2. Vyber záložku **Obrázok** alebo **Video / GIF**
3. Nahraj súbor alebo ho pretiahni do okna
4. Uprav filtre, pridaj text alebo nálepky
5. Použi **AI Generátor** na automatický vtipný text
6. Klikni **Stiahnuť PNG** alebo **Exportovať GIF**

## Štruktúra projektu

```
MEMEGenerator/
├── index.html       # Celá aplikácia (inline CSS + JS)
├── thumbnail.png    # Náhľad projektu (1000×1000px)
└── README.md        # Tento súbor
```

## Autor

**glonco90** — B-MSAP 2026
