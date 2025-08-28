# Assistant Diagnosi Radiologica ILD

Web app standalone (HTML + JS) per supportare la diagnosi radiologica delle malattie interstiziali polmonari (ILD).

## Funzionalità
- Classificazione **UIP pattern** (tipico, probabile, indeterminato, alternativa)
- Identificazione **HP** (tipica / compatibile, fibrotica o non fibrotica)
- Segnali ancillari (**CTD-ILD**, asbestosi)
- Flag **CPFE** (enfisema + fibrosi)
- Criteri di **PPF** (progressive pulmonary fibrosis)
- Generatore di **report sintetico** in italiano
- **Offline**, senza dipendenze esterne

## Uso locale
Scarica/clona il repo e apri `index.html` con il browser (Chrome, Firefox, Edge, Safari).

## Pubblicazione con GitHub Pages
1. Crea un repository pubblico su GitHub (es. `ILD-Radiology-Assistant`).  
2. Carica i file `index.html`, `README.md` e `LICENSE` nella root.  
3. Vai su **Settings › Pages** e imposta **Source = Deploy from a branch**, **Branch = main**, **Folder = /(root)**.  
4. L’app sarà disponibile a un URL tipo: `https://<tuo-username>.github.io/ILD-Radiology-Assistant/`

## Avvertenze
Questo strumento supporta la refertazione radiologica delle ILD e **non sostituisce** il giudizio clinico né la discussione multidisciplinare (MDD).
