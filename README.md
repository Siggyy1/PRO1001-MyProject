# Personlig Hub - Arbeidskrav 2

Dette prosjektet er en enkel nettside bygget som en del av arbeidskravet i emnet. Fokus har vært på korrekt bruk av Git/GitHub, semantisk HTML-struktur og layout-kontroll med CSS Flexbox.

## 🚀 Læringsmål i dette prosjektet
* Oppsett og styring av prosjekt med Git og GitHub.
* Bruk av meningsfulle commit-meldinger og ryddig repo-struktur.
* Konstruksjon av nettside med semantisk HTML og Flexbox.
* Design og styling av et funksjonelt HTML-skjema.

## 🛠️ Tekniske detaljer

### Semantisk HTML
Siden er bygget opp ved hjelp av semantiske elementer som `<header>`, `<nav>`, `<main>`, `<section>` og `<footer>` for å sikre god tilgjengelighet og struktur.

### Flexbox Layout
Flexbox er brukt aktivt for å skape en responsiv og ryddig layout:
* **Navigasjon:** Brukt `display: flex` med `justify-content: space-between` for å skille logo og lenker.
* **Hero-seksjon:** Innholdet er sentrert både vertikalt og horisontalt ved hjelp av Flexbox-egenskaper.
* **Skjema:** Flexbox er brukt for å stable input-feltene vertikalt med jevn avstand.

### Kontakt-skjema
Siden inneholder et kontaktskjema med følgende funksjonalitet:
* Input-felter for navn, e-post og melding med tilhørende `<label>`.
* HTML5-validering (`required` og `type="email"`).
* Hover- og fokus-effekter på knapper og felter for bedre brukeropplevelse.

## 📂 Filstruktur
* `index.html` - Hovedstrukturen til nettsiden.
* `style.css` - All styling og Flexbox-logikk.
* `.gitignore` - Spesifiserer filer som skal ignoreres av Git.
* `LICENSE` - Prosjektets lisens (MIT).