# Accordatore Storico / Historical Tuner

## English

**Chromatic tuner for historical and early music instruments** — a free, no-install web application that runs directly in your smartphone browser.

### Features

- **Robust pitch detection** via the YIN algorithm, supporting frequencies down to ~43 Hz (double basses, bassoons, bass crumhorns)
- **Analogue needle meter** with cent scale (±50¢), green in-tune zone and sharp/flat display
- **Adjustable reference A** from 370 Hz to 480 Hz, with historical presets:
  - 392 Hz — Kammerton
  - 415 Hz — Baroque
  - 422.5 Hz
  - 430 Hz — Classical
  - 435 Hz — Diapason normal (1859)
  - 440 Hz — Modern ISO
  - 442 Hz — Orchestral
  - 466 Hz — Chorton
- **Historical temperaments**:
  - Modern equal temperament
  - Pythagorean
  - Quarter-comma meantone
  - Werckmeister III (1691)
  - Just intonation from C
  - Just intonation from D *(for instruments cut in D: recorders, crumhorns, viols)*
- **Reference tone generator** (sine, triangle, sawtooth) across all octaves, automatically updated on temperament or reference pitch change
- No server, no data sent — everything runs locally in the browser

### How to use

1. Open the link in Chrome on Android (or Safari on iOS)
2. Grant microphone access when prompted
3. Hold the phone near the instrument and play
4. To add the icon to your home screen: three-dot menu → *Add to Home Screen*

### Requirements

A modern browser with Web Audio API and `getUserMedia` support. Tested on Chrome for Android. Requires HTTPS (provided by GitHub Pages).

---


## Italiano

**Accordatore cromatico per strumenti antichi e storici** — applicazione web gratuita, senza installazione, utilizzabile direttamente dal browser del proprio smartphone.

### Caratteristiche

- **Rilevamento del pitch** robusto tramite algoritmo YIN, con supporto fino a ~43 Hz (contrabbassi, fagotti, cromorne basse)
- **Meter ad ago analogico** con scala in cent (±50¢), zona verde di intonazione e indicazione sharp/flat
- **La di riferimento regolabile** da 370 Hz a 480 Hz, con preimpostazioni storiche:
  - 392 Hz — Kammerton
  - 415 Hz — Barocco
  - 422,5 Hz
  - 430 Hz — Classico
  - 435 Hz — Diapason normale (1859)
  - 440 Hz — ISO moderno
  - 442 Hz — Orchestrale
  - 466 Hz — Chorton
- **Temperamenti storici**:
  - Equabile moderno
  - Pitagorico
  - Mesotonico ¼ di comma
  - Werckmeister III (1691)
  - Intonazione giusta da Do
  - Intonazione giusta da Re *(per strumenti tagliati in Re: flauti dolci, cromorne, viole)*
- **Generatore di toni di riferimento** (seno, triangolo, dente di sega) su tutte le ottave, aggiornato automaticamente al cambio di temperamento e di La
- Nessun server, nessun dato inviato — tutto gira localmente nel browser

### Come si usa

1. Apri il link nel browser Chrome su Android (o Safari su iOS)
2. Concedi l'accesso al microfono quando richiesto
3. Avvicina il telefono allo strumento e suona
4. Per aggiungere l'icona alla schermata home: menu tre puntini → *Aggiungi alla schermata Home*

### Requisiti

Browser moderno con supporto Web Audio API e `getUserMedia`. Testato su Chrome per Android. Richiede connessione HTTPS (già garantita da GitHub Pages).

