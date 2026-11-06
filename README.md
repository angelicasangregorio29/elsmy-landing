# elsmy-landing# Elsmy — Landing page MVP

Landing page di validazione per **Elsmy – My Emotional Light Security**: raccoglie email per la beta privata e distingue l'interesse personale da quello aziendale.

Progetto separato dall'app ([angelicasangregorio29/elsmy](https://github.com/angelicasangregorio29/elsmy)).

## Avvio
Apri `index.html` con un doppio clic. Tailwind CSS e Alpine.js arrivano da CDN: serve solo la connessione a internet.

## Collegare la raccolta email
1. Crea un form gratuito su [formspree.io](https://formspree.io).
2. In `index.html` cerca `FORM_ENDPOINT` e sostituisci `https://formspree.io/f/IL_TUO_ID` con il tuo endpoint.

Finché resta il segnaposto, il form mostra la conferma ma **non salva** le email.

## Questionario e Google Analytics
Nello stesso blocco di `index.html` trovi:
- `QUESTIONARIO_URL`: il link al questionario v2. Dopo l'iscrizione compare il pulsante "Compila il questionario".
- `GA_ID`: il tuo ID Google Analytics 4 (es. `G-ABC123XYZ`). Ogni iscrizione viene registrata come evento `generate_lead`, utile per misurare la conversione (KR4 ≥ 10%).

## Pubblicare online
Settings → Pages → Branch `main` / root → Save. La pagina sarà su `https://angelicasangregorio29.github.io/elsmy-landing/`.

## Da personalizzare
- Email di contatto `ciao@elsmy.app` (footer e sezione aziende)
- Link al canale YouTube Elsmy Channel, quando sarà online
