# rbWave

[English](README.md) • [Italiano](README_it.md)

Tema Obsidian con vibe **VaporWave / RetroWave**, pensato per chi passa molte ore davanti allo schermo: programmatori, ingegneri, lettori intensivi.

![rbWave — palette Synthwave](background.png)

![rbWave — palette Tokyo Night](background2.png)

## Filosofia

- **Mai nero puro / mai bianco puro** — sfondo indaco profondo, testo bianco-caldo.
- **Neon usato con parsimonia** — accenti riservati a heading, link, focus, syntax highlighting. Il body resta calmo.
- **Contrasto WCAG AA** sul testo principale.
- **Effetti retro opzionali** (glow, griglia prospettica, scanline CRT): tutti disattivati di default, attivabili da Style Settings.
- **Vibe da programmazione**: heading monospace di default, prefissi `#`, `##` davanti ai titoli, code block con bordo neon, status bar in monospaced.

## Installazione

1. Copia la cartella `rbWave/` in `<vault>/.obsidian/themes/rbWave/`
2. Settings → Appearance → Theme → seleziona **rbWave**
3. Installa il plugin [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
4. Apri Settings → Style Settings → rbWave

## Varianti (Style Settings)

| Sezione | Opzioni |
|---|---|
| **Palette** | Synthwave (default) · Outrun · Miami · Tokyo Night · Soft Reading |
| **Background depth** | Deep · Medium · Soft |
| **Effetti** | Retro grid · Neon glow · CRT scanlines (tutti off di default) |
| **Tipografia** | Heading monospace on/off · font text · font mono · size · line-height |
| **Accenti** | Color picker primario / secondario per override |

### Suggerimenti d'uso

- **Sessioni di codice lunghe** → palette `Tokyo Night` o `Soft Reading`, glow off, depth medium.
- **Vibe massima retrowave** → `Synthwave` + grid on + glow on (occhio al mal di testa dopo un'ora).
- **Lettura prolungata di note** → `Soft Reading`, line-height 1.7, mono headings off.

## Struttura

```
rbWave/
├── manifest.json
├── theme.css
├── LICENSE
├── README.md
└── README_it.md
```

## Licenza

[GPL v2](LICENSE) — usa, fork, modifica.
