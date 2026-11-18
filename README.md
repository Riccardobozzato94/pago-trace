# PagoTrace

Demo interattiva di **solleciti per fatture non pagate**. L'AI bozza il tono giusto, l'umano approva, ogni invio è loggato.

**Live demo:** https://riccardobozzato94.github.io/pago-trace/

## Cosa dimostra
- Tabella decisionale `giorno +3 → cordiale`, `+10 → fermo`, `+20 → ultimo avviso`, implementata in codice.
- **Output AI reale** catturato il 18/11/2026 (`dots-studio/dots-3-note-preview:free`): oggetto, testo e motivo del tono generati correttamente → **firmato dall'umano** prima dell'invio.
- Nessun invio reale, dati finti dichiarati.

## Stack
HTML/CSS/JS statico, GitHub Pages. In produzione: Cloudflare Workers + D1, Gemini free tier, Make free, invio SMTP solo dopo approvazione.

Parte del portfolio AI Operations di Riccardo Bozzato, PMP®.
