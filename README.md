# Verifizierte iPhone-Treffer

Statischer Atom-Feed für neue, aktuell kaufbare iPhones mit gerätespezifisch verifizierter Firmware.

- Feed: `feed.xml`
- Kleine Landingpage: `index.html`
- Feed-URL: `https://raw.githubusercontent.com/rss-input/verified-iphone-finds/main/feed.xml`

## Einen Treffer ergänzen

1. Den neuen `<entry>`-Block direkt unter `<author>` einfügen, damit der neueste Treffer oben steht.
2. Eine dauerhaft eindeutige `<id>` verwenden, bevorzugt mit Händler und Artikelnummer.
3. `<updated>` im Feed-Kopf sowie `<published>` und `<updated>` des Eintrags im ISO-8601-Format setzen.
4. Sonderzeichen in Attributen und URLs XML-gerecht maskieren, insbesondere `&amp;`.
5. Vor dem Veröffentlichen prüfen, dass `feed.xml` wohlgeformtes XML ist.
