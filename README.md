# ausbildungsbuddy-web
AusbildungsGREATER 🚀

Dein interaktiver Quiz‑ und Info‑Coach für Ausbildungs­entscheidungen

AusbildungsGREATER unterstützt Schüler*innen dabei, spielerisch ihre Interessen und Stärken herauszufinden und passende Ausbildungsberufe zu entdecken. Mit einem 10‑Fragen‑Selbsttest, aktuellen Vergütungsdaten und detaillierten Berufsinformationen liefert der Bot maßgeschneiderte Empfehlungen – inklusive Tipps zur Bewerbung und Karriereausblick.

🧩 Bot‑Beschreibung

Name: AusbildungsGREATER 🚀

Entwickler: inteGREATer Aachen

Zielgruppe: Schüler*innen, die sich für eine Ausbildung interessieren

Funktionen:

Interaktiver 10‑Fragen‑Selbsttest (A/B/C‑Antworten)

Live‑Daten via RAG aus BIBB‑Vergütungs‑Tabellen und Berufenet‑API

Top‑3‑Berufe mit Steckbriefen (Aufgaben, Skills, Gehalt, Karriere)

Bewerbungshilfe: Lebenslauf‑Check, Anschreiben‑Vorlage, Interview‑Tipps

Regionale Stellen‑Suche und Bewerbungstipps

Mehrsprachige Option (Deutsch/Englisch)

✨ Hauptfeatures

Adaptive Frage‑Flows mit Feedback und Fortschrittsanzeige

Digitale Badges zur Motivation nach Testabschluss

Steuerkommandos: Zurück, Wiederholen, Quiz abbrechen

Barrierefrei: Klare Sprache, semantisch eingesetzte Emojis

Analytics‑Hook: (optional) unsichtbares Tracking von Antwortzeiten und Abbruchpunkten

📋 Voraussetzungen

ChatGPT Plus Account für den GPT‑Builder

Öffentliche Freigabe des GPT‑Bots

Zugriff auf BIBB‑Excel‑Dateien und Berufenet‑API (API‑Key: infosysbub‑berufenet)

🚀 Einbindung als Webseite

Variante A: iFrame‑Embed via GitHub Pages

GPT‑Link öffentlich teilen (My GPTs → Erstellen → Öffentlich) und URL kopieren

GitHub‑Repo mit index.html erstellen (siehe unten)

iFrame in index.html auf deinen GPT‑Link verweisen

GitHub Pages aktivieren (Settings → Pages → Branch main → root)

Variante B: Netlify oder Vercel

Repo verbinden und Deployment durchführen

Beispiel index.html

<!DOCTYPE html>
<html lang="de">
<head><meta charset="utf-8"><title>AusbildungsGREATER</title>
<style>body,html{margin:0;padding:0;height:100%}iframe{width:100%;height:100%;border:none}</style>
</head>
<body>
  <iframe src="DEIN_GPT_LINK" allow="clipboard-write"></iframe>
</body>
</html>

📄 Lizenz

MIT License © 2025 inteGREATer Aachen
