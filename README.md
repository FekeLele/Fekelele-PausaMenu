# Fekelele Pause Menu

Menu Pausa moderno per FiveM, stile nero/grigio, con logo personalizzato.

## Caratteristiche
- Interfaccia elegante, responsive e animata
- Comandi e tasti personalizzabili (ESC)
- Compatibile con ox_lib e nativo
- Facile da integrare in qualsiasi server

## Installazione
1. Copia la cartella `Fekelele_pausamenu` in `resources`.
2. Aggiungi al tuo `server.cfg`:
   ```
   ensure Fekelele_pausamenu
   ```
3. (Opzionale) Aggiungi le dipendenze in `fxmanifest.lua` se usi ESX o ox_lib.

## Utilizzo
- Premi **ESC** per aprire/chiudere il menu pausa.
- Personalizza i testi e le azioni modificando i file in `html/` e `client/`.

## Personalizzazione
- Cambia il logo modificando la riga `<img class="menu-logo" ...>` in `html/index.html`.
- Modifica colori e stile in `html/style.css`.

## Crediti
- Design: Fekelele
- Logo: [logodever.png](https://i.postimg.cc/dVvSL9fZ/logodever.png)

---
Per supporto o idee, contatta Fekelele su Discord!

https://discord.gg/VnANeHYP
