# Rufklar – Landingpages (MVP)

Drei eigenständige, komplett self-contained Landingpages für **Rufklar** – Service zum Entfernen negativer Google-Bewertungen mit Erfolgsprinzip.

## Modell

- **25 €** pro erfolgreicher Löschung
- **Ab der 5. Löschung im selben Auftrag: 20 € pro Stück** (Staffel greift automatisch)
- Kein Erfolg = keine Kosten · Rechnung erst nach Abschluss, 14 Tage Zahlungsfrist
- Beauftragung in ~2 Minuten (Google-Maps-Link einreichen)

## Die drei Varianten

| Datei | Konzept | Besonderheiten |
|---|---|---|
| `rufklar-1-direkt.html` | Der Deal – dunkel, brutal-direkt | Interaktiver Preisrechner mit Slider, Sticky-Mobile-CTA |
| `rufklar-2-vertrauen.html` | Vertrauen – hell, seriöses B2B (Petrol) | Preisrechner mit freier Mengenwahl (1–20, ab 5 → 20 €/Stück), Vergleichstabelle, Fall-Beispiel-Animation (Strike + „Entfernt“-Stempel beim Reinscrollen), FAQ-Accordion |
| `rufklar-3-klartext.html` | Klartext – warm, editorial | Preis als Kassenbon, „Was wir nicht machen“ als Vertrauensanker |

Alle Seiten: eine Datei, Inline-CSS/JS, keine Frameworks, responsive, `prefers-reduced-motion`-Unterstützung.

## Nutzung

Datei herunterladen bzw. klonen und im Browser öffnen – kein Build-Step, kein Backend. Formulare bauen aktuell eine `mailto:`-Vorlage; für den Live-Betrieb an ein Formular-Backend anbinden und Impressum/Datenschutz ergänzen.
