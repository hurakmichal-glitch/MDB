# MDB - Kodi Addons Repository

Kodi repository pre TV, Filmy a Seriály.

## Dostupné Addons

- **Eagle BLVCK** - Addon pre Eagle BLVCK obsah
- **Freeview SK** - Bezplatný obsah zo Slovenska
- **Prehrajto** - Streaming obsah z Prehrajto
- **SKT Online** - SKT Online streaming
- **Stream Cinema** - Filmový streaming obsah

## Inštalácia

### Metóda 1: Inštalácia z URL
1. V Kodi prejdite na: Nastavenia → Systém → Addons → Inštalovať zo ZIP súboru
2. Zdroj → Pridať zdroj
3. Vložte URL: `https://raw.githubusercontent.com/hurakmichal-glitch/MDB/main/`
4. Názov: `MDB Repository`
5. Potom prejdite na Inštalovať z úložiska → MDB Repository a vyberte `repository.mdb`

### Metóda 2: Manuálna inštalácia
1. Stiahnite si `repository.mdb.zip` z [`releases`](https://github.com/hurakmichal-glitch/MDB/releases)
2. V Kodi prejdite na: Nastavenia → Systém → Addons → Inštalovať zo ZIP súboru
3. Vyberte stiahnený súbor

## Štruktúra Repositáru

```
MDB/
├── repository.mdb/          # Metadata repositáru
│   ├── addon.xml
│   ├── icon.png
│   └── fanart.jpg
├── zips/                    # ZIP balíčky addonov
│   ├── plugin.video.eagle.blvck.zip
│   ├── plugin.video.freeview.sk-1.2.4.zip
│   ├── plugin.video.prehrajto.zip
│   ├── plugin.video.sktonline.zip
│   └── plugin.video.stream-cinema.zip
├── addons.xml               # Manifest všetkých addonov
├── addons.xml.md5           # Checksum pre kontrolu integrity
└── README.md
```

## Technické Detaily

- **Repository ID**: `repository.mdb`
- **Verzia**: 1.0.0
- **Minimálna Kodi verzia**: 2.6.0
- **Licencia**: MIT

## Troubleshooting

Ak Kodi nevidí addony:
1. Skontrolujte internetové pripojenie
2. Vyčistite cache v Kodi: Nastavenia → Systém → Taká nastavení → Vyčistiť balíčky addonov
3. Skúste znova pridať zdroj

## Licencia

MIT License

## Support

Kontakt: [@hurakmichal-glitch](https://github.com/hurakmichal-glitch)
