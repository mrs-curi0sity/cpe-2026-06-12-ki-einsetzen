# umgebung einrichten
source .venv/bin/activate
pip install ipykernel
python3 -m ipykernel install --user --name=ukb-ki-einsetzen

# präsentation erzeugen:

im Quarto Terminal 
> quarto preview /Users/lena/code/CPE_Schulungen/2026-06-12-KI-Einsetzen/slides.ipynb --no-browser


# präsentation anzeigen

oder oben im ipynb ...> outline

oder url aus Terminal (z.B. http://localhost:7868/)

oder erzeugtes slides.html mit Browser öffnen

# pdf erzeugen

?print-pdf in der url. also z.B.

http://127.0.0.1:4109/?print-pdf



# powerpoint erzeugen
> .. --to pptx


# Modelle
Qwen3-35B => Großes Sprachmodell, multilingual, stark in Reasoning +

Gemma-4-4B => Googles kleines Modell, schnell, leichtgewichtig

Qwen3-Embedding-4B => Kein Chatmodell – erzeugt Vektoren für Semantic Search / RAG, Gut für RAG-Erklärung


# Ablauf
# Workshop: KI einsetzen – Ablaufplan

**Datum:** 12. Juni 2026, 09:00–17:00 Uhr  
**Ort:** A09.0.018 (CPE) – Seminarraum, Venusberg-Campus 1, Bonn  
**Max. TN:** 12 | **Zielgruppe:** Ärzte, Wissenschaftler, Führungskräfte

---

## Ablauf

| Zeit | Block | Format | Inhalt |
|---|---|---|---|
| 09:00–09:20 | **Warm-up** | Interaktiv | Vorstellung (du + TN). Frage ans Plenum: *„Was erhoffst du dir heute?"* → Whiteboard |
| 09:20–09:50 | **Vortrag A** | Mini-Vortrag | Was ist KI, was kann sie? Regression, Klassifikation, Clustering, Bildanalyse, Textgenerierung – mit klinischen Beispielen |
| 09:50–10:30 | **Brainstorming 1** | Gruppenarbeit | *„Welche Probleme habt ihr?"* – Post-its sammeln, clustern. Noch kein Kommentar. |
| 10:30–10:45 | ☕ Pause | | |
| 10:45–11:15 | **Vortrag B** | Mini-Vortrag | KI-Level: selbst trainieren / finetunen / API lokal / API extern – wann macht was Sinn? |
| 11:15–12:00 | **Brainstorming 2** | Gruppenarbeit | Post-its aus Runde 1 neu bewerten: *„Welches Level passt zu eurem Problem?"* – du gehst rum, kommentierst |
| 12:00–13:00 | 🍽️ Mittagspause | | |
| 13:00–15:00 | **Clinic** | Pitch + Diskussion | TN pitchen je ~5–8 min: *„Was nervt euch / was wollt ihr lösen?"* → du gibst strukturierte Einschätzung live, Gruppe kommentiert |
| 15:00–15:15 | ☕ Pause | | |
| 15:15–16:00 | **Vortrag C** | Mini-Vortrag | Ausblick: RAG, Agentic Systems, Knowledge Graphs, Sensorik, Body-Brain |
| 16:00–16:45 | **Roadmaps** | Einzel + Plenum | Jeder skizziert 1-Pager: Problem → Methode → Daten → nächster Schritt → kurz vorstellen |
| 16:45–17:00 | **Abschluss** | Plenum | Feedback, offene Fragen, Angebote weiterer Zusammenarbeit |

---

## Hinweise

- **Interaktivität fördern:** Post-its vor Meldungen – niemand muss sich "melden"
- **Clinic-Einstieg:** *„5 Minuten, kein Vortrag, einfach erzählen was nervt"*
- **Vortrag C** kommt nach der Pause – Energie nutzen
- **Keine Teilnehmerliste** → Clinic-Themen sind offen, von Excel-Datum bis MRT-Analyse alles möglich