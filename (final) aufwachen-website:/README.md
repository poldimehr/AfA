# Aufwachen für Anfänger — Website

## Was ist drin?

```
aufwachen-website/
├── index.html                      ← Landing Page (deine bewährte Version + Systeme.io + Legal-Links)
├── legal.html                      ← Impressum + Datenschutz
├── letter.png                      ← Brief-Bild für die Landing Page
└── 3-schritte-mechanismus/
    └── index.html                  ← VSL-Seite (Video-Training)
```

## WICHTIG zu den Bildern

Diese Version nutzt für 8 Bilder noch die Figma-CDN-URLs (Logo, About-Bilder,
Hintergrund-Fades, Stern, Video-Vorschau, PDF-Banner). Die laufen ~7 Tage
nach Generierung ab. Du kannst direkt deployen und hast Zeit zum Testen.

Für **permanent**: Bilder selbst aus Figma exportieren, in einen `assets/`
Unterordner legen, und die Figma-URLs in der index.html durch lokale
Pfade ersetzen. Dann ändert sich nichts mehr.

## Live deployen

1. Geh auf https://app.netlify.com/drop
2. Ziehe diesen ganzen Ordner ins Browserfenster
3. Warte 30 Sekunden — fertig.
