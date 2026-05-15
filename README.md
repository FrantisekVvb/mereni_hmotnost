# Rovnoramenné váhy — interaktivní model

Statická webová simulace laboratorních rovnoramenných vah: přetahování jablka, rohlíku a závaží na misky, dynamické naklonění ramene a sekce **Ověření hmotnosti**.

## Spuštění

Projekt nepotřebuje build ani server — stačí otevřít `index.html` v prohlížeči (nebo použít libovolný lokální statický server).

```bash
python3 -m http.server 8080
```

Pak v prohlížeči: `http://localhost:8080`

## Struktura

| Cesta | Popis |
|--------|--------|
| `index.html` | UI, SVG váhy, skript simulace a ověření |
| `rovnoramenne_vahy/assets/` | SVG obrázky (jablko, rohlík, pomocná grafika) |

## GitHub Pages (volitelně)

V nastavení repozitáře: **Settings → Pages → Branch `main` / root** — nasadí se stejný statický obsah.
