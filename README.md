# KI-Tool Compliance Assistant DE

> ⚠ Kein Rechtsgutachten. Ersetzt keine Fachberatung. Nutzung auf eigene Verantwortung.

Ein strukturiertes 4-Prompt-System das deutschen IT-Entscheidern, HR- und 
Abteilungsleitern hilft, neue KI-Tools intern vorzubereiten – bevor die 
Rechtsabteilung oder der Betriebsrat fragt.

Das System prüft ein Tool gegen die vier relevantesten Hürden im deutschen 
Unternehmenskontext: DSGVO, BetrVG § 87, EU AI Act und IT-Sicherheit.

---

## Wie es funktioniert

Drei Prompts in einem Chat – du gibst Tool-Name und Einsatzbereich ein, 
der Rest läuft sequenziell. Optional: ein vierter Prompt in einem neuen 
Chat zur unabhängigen Validierung des Reports.

Funktioniert in ChatGPT, Claude, Gemini und jedem anderen aktuellen LLM.
Kein Setup, keine Registrierung.

**Hinweis:** Für Prompt 2 und Prompt 4 Phase 2 ist Webzugriff empfohlen. 
Ohne Webzugriff arbeitet das System trotzdem – offene Punkte werden dann 
explizit als [AKTUALITÄT UNBESTÄTIGT] markiert.

---

## Dateien

- `prompts.md` – Alle 4 Prompts zum direkten Kopieren
- `prompts.py` – Die gleichen Prompts als Python-Datei für Entwickler

---

## Feedback & Vorschläge

Dieses System ist ein erster Stand – kein fertiges Produkt. Wenn du es 
nutzt und etwas nicht funktioniert, eine Rechtslage fehlt, oder du einen 
besseren Ansatz siehst: Rückmeldungen sind ausdrücklich willkommen.

Was hat funktioniert? Was hat gefehlt? Welches Tool hast du geprüft?

Feedback gerne als Issue oder per Nachricht.

---

## Disclaimer

Dieses System und alle daraus generierten Reports ersetzen keine 
Rechtsberatung, keine Datenschutzprüfung und keine IT-Sicherheitsanalyse 
durch Fachpersonal. Alle Outputs dienen ausschließlich als strukturierte 
Vorarbeit für Rechts-, IT- und HR-Fachabteilungen. Die Bewertung gilt nur 
für den jeweils beschriebenen Einsatzbereich – abweichende Nutzung 
erfordert eine neue Prüfung. Die Verantwortung für finale Entscheidungen 
liegt beim Nutzer und den zuständigen Fachabteilungen.
