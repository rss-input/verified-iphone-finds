# Verifizierte iPhone-Treffer

Automatisch aktualisierter Atom-Feed für neue, aktuell kaufbare iPhones mit gerätespezifisch verifizierter Firmware.

- Feed: `feed.xml`
- Kleine Landingpage: `index.html`
- Feed-URL: `https://raw.githubusercontent.com/rss-input/verified-iphone-finds/main/feed.xml`
- Aktualisierung: automatisch alle zwei Stunden

## Recherchen

- **Recherche A:** iPhone 15/16/17 Pro und Pro Max ab 256 GB, exakt iOS 26.0 oder 26.0.1.
- **Recherche B:** iPhone 15 Pro und Pro Max ab 256 GB, iOS 17.0 bis einschließlich 17.3.1.

Aufgenommen werden nur konkrete, aktuell kaufbare Angebote mit gerätespezifischem Firmware-Nachweis. Verkaufte, reservierte, abgelaufene oder nicht direkt verifizierbare Kandidaten werden ausgeschlossen. Angebotsnummern, URLs und Cross-Listings werden dedupliziert.

## Automatische Pflege

Ein aktiver Codex-Heartbeat führt beide weltweiten Recherchen fort und aktualisiert `feed.xml` direkt auf dem Hauptzweig. Der Feed-Zeitstempel ändert sich nur bei echten neuen Einträgen.
