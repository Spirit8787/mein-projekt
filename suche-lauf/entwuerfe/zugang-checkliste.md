# Entwurf: Zugang-Checkliste (Prüfungen 1, 2, 12)

Diese Schritte müssen zuerst passieren. Alles andere wirkt erst, wenn Google deine beiden Shops überhaupt findet. Mach die Punkte **in dieser Reihenfolge** ab.

Für **beide Shops getrennt** (klangschalencenter.ch UND spiritwellness.ch):

## Schritt 1 — Shopify: ist der Shop öffentlich?

1. In Shopify einloggen (für jeden Shop einzeln).
2. **Einstellungen → Einstellungen → Passwort** öffnen.
3. Prüfen: "Passwortseite aktivieren" ist **nicht angehakt**.
4. Falls doch: deaktivieren und speichern.

Solange ein Passwortschutz aktiv ist, kann Google deine Seite nicht lesen.

## Schritt 2 — Shopify: Suchmaschinen erlauben

1. **Verkaufskanäle → Online-Shop → Einstellungen** öffnen.
2. Bei "Suchmaschinen" prüfen: "Deine Website in Suchmaschinen anzeigen" ist **angehakt**.
3. Prüfe auch: keine `noindex`-Angabe im Theme-Code oder in den Produktbeschreibungen.

## Schritt 3 — Google Search Console

1. [search.google.com/search-console](https://search.google.com/search-console) öffnen (Gratis-Google-Account genügt).
2. **Property hinzufügen** → "Domain" → `klangschalencenter.ch` eintragen.
3. Verifizierung per DNS-TXT-Record (Google gibt dir einen Text, den dein Domain-Provider einträgt — nur einmal nötig).
4. Nach Verifizierung: **Sitemaps → Sitemap hinzufügen** → `sitemap.xml` eingeben (Shopify erzeugt die automatisch unter `klangschalencenter.ch/sitemap.xml`).
5. Dasselbe für `spiritwellness.ch`.
6. In Search Console unter **Indexierung → Seiten** nach 1–2 Wochen prüfen, wie viele Seiten indexiert sind.

**Dieser Schritt alleine macht dich auffindbar.** Ohne Search Console ist alles andere Zeitverschwendung.

## Schritt 4 — Branchenverzeichnisse (Prüfung 12)

Trage BEIDE Firmen in den folgenden Schweizer Verzeichnissen ein. Pro Firma je eigener Eintrag. Platzhalter sind rot markiert.

Pflicht:
- [local.ch/mein-eintrag](https://www.local.ch/) — die wichtigste Schweizer Suche
- [search.ch](https://www.search.ch/) — zweitwichtigste
- [moneyhouse.ch](https://www.moneyhouse.ch/) — kostenlos, Google vertraut diesem Handelsregister-Verzeichnis
- [swissfirms.ch](https://www.swissfirms.ch/) — IHK-Verzeichnis

Thematisch sinnvoll:
- Klangschalencenter → yoga-schweiz.ch, klangverzeichnis.ch, meditation-schweiz.ch
- Spirit Wellness → wellness-schweiz.ch, esoterikverzeichnis.ch

**In jedem Eintrag exakt dieselben Stammdaten eintragen:**

```
Firma:         [FIRMENNAME eintragen]
Adresse:       [STRASSE]
PLZ Ort:       [PLZ ORT]
Telefon:       [TELEFONNUMMER]
E-Mail:        [E-MAIL]
Website:       https://www.klangschalencenter.ch   (bzw. spiritwellness.ch)
Öffnungszeiten: [SO EINTRAGEN WIE IM SHOP]
```

Wichtig: Jede Abweichung (Str. vs Strasse, alte Telefonnummer, anderer Name) verwirrt Google.

## Reihenfolge und Zeitbedarf

| Schritt | Dauer | Wirkung sichtbar nach |
|---|---|---|
| 1 Shopify Passwort weg | 2 Min | sofort |
| 2 Suchmaschinen erlauben | 2 Min | sofort |
| 3 Search Console + Sitemap | 30 Min | 1–3 Wochen |
| 4 Verzeichnisse (je Firma) | 2–3 Stunden | 2–6 Wochen |

Insgesamt ein halber Tag Arbeit. Das löst 80% des Sichtbarkeitsproblems.
