# Hotsflow Design

Riferimento di design/UI per lo sviluppo dell'App Shell Hotsflow e dei moduli
(Housekeeping, Turni, Transfer). Contiene prototipi statici HTML/CSS —
**nessun backend, nessuna logica applicativa reale, nessuna dipendenza da
Supabase/Core**. Sono materiale di riferimento visivo/strutturale per chi
implementa, non codice di produzione.

## File

- **`app-shell-prototype.html`** — prototipo dell'App Shell Hotsflow: shell
  di navigazione globale (sidebar, Home per ruolo, Moduli/Team/Impostazioni),
  stati dei moduli, stati di sistema condivisi, note su deep-linking e
  gerarchia dell'informazione, confronto delle due opzioni di navigazione
  mobile secondaria. Stato: **congelato** dopo una serie di correzioni
  architetturali (naming generico dei moduli, modello di autorizzazione
  Core-based, distinzione fra comportamento legacy e architettura target).
  Live: https://claude.ai/code/artifact/8a5d8c47-680e-405a-b6f5-ab80cc5a7f1d

- **`design-standard-v2.html`** — il design system alla base del prototipo:
  token (colori, tipografia, spaziatura, ombre, motion), componenti UI
  (bottoni, form, tabelle, modali, pannelli, navbar), principi di utilizzo e
  note di accessibilità.
  Live: https://claude.ai/code/artifact/e8a11acd-c661-463b-a896-b9fcdf0a9de0

Entrambi i file sono self-contained (HTML/CSS/poco JS inline, nessuna build,
nessuna dipendenza esterna oltre Google Fonts) — si aprono direttamente in un
browser.

## Come usarli

- Riferimento visivo/strutturale durante l'implementazione reale dell'App
  Shell e dei moduli — non vanno copiati come codice di produzione.
- I link "Live" sopra puntano alle versioni pubblicate come Claude Artifact;
  i file in questo repo sono lo snapshot corrispondente, per condivisione e
  versionamento fuori da quella piattaforma.
