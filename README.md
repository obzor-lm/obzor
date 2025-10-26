# Strona Webinaru

Nowoczesna, responsywna strona internetowa do promocji i rejestracji na webinar.

## Funkcjonalności

- **Responsywny design** - działa na wszystkich urządzeniach (desktop, tablet, mobile)
- **Licznik czasu** - odliczanie do rozpoczęcia webinaru
- **Formularz rejestracyjny** - z walidacją danych
- **Płynne przewijanie** - nawigacja po sekcjach strony
- **Animacje scroll** - elementy pojawiają się podczas przewijania
- **Nowoczesny design** - gradient, cienie, zaokrąglone rogi

## Struktura plików

```
.
├── index.html      # Główny plik HTML
├── styles.css      # Stylowanie strony
├── script.js       # Interaktywność (licznik, formularz, animacje)
└── README.md       # Dokumentacja
```

## Sekcje strony

1. **Hero** - nagłówek z tytułem, datą webinaru i licznikiem czasu
2. **O webinarze** - główne tematy i korzyści
3. **Agenda** - szczegółowy program webinaru
4. **Rejestracja** - formularz zapisu na webinar
5. **Stopka** - informacje kontaktowe i linki społecznościowe

## Uruchomienie

Wystarczy otworzyć plik `index.html` w przeglądarce internetowej.

Alternatywnie, możesz użyć lokalnego serwera:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve

# PHP
php -S localhost:8000
```

Następnie otwórz w przeglądarce: `http://localhost:8000`

## Personalizacja

### Zmiana daty webinaru

W pliku `script.js` zmień datę w linii:
```javascript
const targetDate = new Date('2025-11-15T18:00:00').getTime();
```

### Zmiana kolorów

W pliku `styles.css` zaktualizuj zmienne CSS:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... */
}
```

### Modyfikacja treści

Edytuj plik `index.html` aby zmienić:
- Tytuły i opisy
- Program webinaru (agenda)
- Dane kontaktowe
- Linki społecznościowe

## Technologie

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables, Animations)
- Vanilla JavaScript (ES6+)
- Responsive Design
- Intersection Observer API

## Wsparcie przeglądarek

- Chrome (najnowsza wersja)
- Firefox (najnowsza wersja)
- Safari (najnowsza wersja)
- Edge (najnowsza wersja)

## Licencja

Projekt dostępny jako przykładowa strona webinaru. Możesz swobodnie modyfikować i wykorzystywać kod.
