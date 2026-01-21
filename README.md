# Harmonia Joanna Kaczmarek - Strona internetowa

Nowoczesna, szybka i bezpieczna strona internetowa zbudowana z użyciem Astro + Tailwind CSS.

## 🚀 Technologie

- **[Astro](https://astro.build/)** - Nowoczesny generator stron statycznych
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Netlify](https://netlify.com/)** - Hosting i formularze kontaktowe

## 📁 Struktura projektu

\`\`\`
/
├── public/
│   ├── images/         # Obrazki (do uzupełnienia)
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro   # Główny layout (header + footer)
│   ├── pages/
│   │   ├── index.astro           # Strona główna
│   │   ├── o-mnie.astro          # O mnie
│   │   ├── kontakt.astro         # Kontakt
│   │   ├── polityka-prywatnosci.astro
│   │   └── oferta/
│   │       ├── index.astro       # Lista usług
│   │       ├── coaching.astro
│   │       ├── dzwiekoterapia.astro
│   │       └── szkolenia.astro
│   └── styles/
│       └── global.css    # Style globalne + Tailwind
├── netlify.toml          # Konfiguracja Netlify
└── package.json
\`\`\`

## 🛠️ Komendy

| Komenda           | Opis                                     |
| :---------------- | :--------------------------------------- |
| \`npm install\`     | Instalacja zależności                    |
| \`npm run dev\`     | Serwer deweloperski \`localhost:4321\`     |
| \`npm run build\`   | Budowanie wersji produkcyjnej do \`./dist/\` |
| \`npm run preview\` | Podgląd wersji produkcyjnej lokalnie     |

## 📷 Obrazki do uzupełnienia

Przed wdrożeniem należy dodać obrazki do folderu \`public/images/\`:

- \`hero-bg.jpg\` - Tło sekcji hero
- \`joanna-portrait.jpg\` - Portret na stronę O mnie
- \`joanna-session.jpg\` - Zdjęcie z sesji
- \`coaching.jpg\`, \`dzwiekoterapia.jpg\`, \`szkolenia.jpg\` - Karty usług
- \`sensoryczna-podroz.jpg\`, \`motanka.jpg\` - Warsztaty

## 🌐 Deployment na Netlify

### Automatyczny (zalecany):
1. Połącz repozytorium GitHub z Netlify
2. Netlify automatycznie zbuduje i wdroży stronę przy każdym pushu

### Ręczny:
1. Uruchom \`npm run build\`
2. Przeciągnij folder \`dist/\` na Netlify Drop

## 📝 Formularz kontaktowy

Formularz używa wbudowanej obsługi formularzy Netlify. Po wdrożeniu:
1. Przejdź do Netlify Dashboard → Forms
2. Formularz "contact" pojawi się automatycznie
3. Możesz ustawić powiadomienia email

## 🔧 Zmiana domeny

Po wdrożeniu na Netlify:
1. Przejdź do Site settings → Domain management
2. Dodaj własną domenę \`harmonia-jk.pl\`
3. Skonfiguruj DNS u dostawcy domeny (OVH)

## 📄 Licencja

Wszelkie prawa zastrzeżone © Harmonia Joanna Kaczmarek
