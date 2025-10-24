# S.D Pro - Landing Stranica

Moderna, responzivna landing stranica za S.D Pro - firmu koja se bavi izradom nameštaja po meri.

## Karakteristike

- **Responzivan dizajn** - Prilagođen za sve uređaje (desktop, tablet, mobilni)
- **Moderna UI/UX** - Čist i profesionalan dizajn
- **Animacije** - Smooth scroll animacije i interaktivni elementi
- **Sekcije:**
  - Hero sekcija sa pozivom na akciju
  - O nama - predstavljanje firme
  - Usluge - prikaz svih usluga
  - Galerija - pregled realizovanih projekata
  - Zašto S.D Pro - prednosti
  - Kontakt forma

## Tehnologije

- HTML5
- CSS3 (sa CSS Grid i Flexbox)
- Vanilla JavaScript
- Google Fonts (Poppins)

## Struktura fajlova

```
/
├── index.html      # Glavna HTML stranica
├── styles.css      # CSS stilovi
├── script.js       # JavaScript funkcionalnost
└── README.md       # Dokumentacija
```

## Uputstvo za korišćenje

1. Otvorite `index.html` u web browser-u
2. Za deployment na server, samo upload-ujte sve fajlove u root direktorijum

## Personalizacija

### Promena boja

U `styles.css` fajlu, možete promeniti glavne boje u `:root` sekciji:

```css
:root {
    --primary-color: #2c3e50;      /* Glavna boja */
    --secondary-color: #e67e22;    /* Akcentna boja */
    --accent-color: #3498db;       /* Dodatna boja */
}
```

### Dodavanje slika

Trenutno stranica koristi placeholder-e za slike. Da biste dodali prave slike:

1. Kreirajte folder `images/` u root direktorijumu
2. Dodajte slike u taj folder
3. U HTML-u, zamenite `.gallery-image-placeholder` div-ove sa `<img>` tagovima

### Kontakt informacije

U `index.html` fajlu, promenite kontakt informacije u sekciji `#contact`:
- Adresa
- Telefon
- Email
- Radno vreme

## Browser podrška

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Licenca

© 2024 S.D Pro. Sva prava zadržana.
