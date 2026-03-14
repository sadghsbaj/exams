# Lernmethoden & Technische Umsetzung

## 1. Lernübersichten (Chunking)

- **Methode:** Komplexe Themen in strukturierte, verdauliche Blöcke herunterbrechen.
- **Umsetzung:** Markdown-Dateien im Svelte-Frontend rendern (ggf. als eigene Components). Dient als ständige Wissensdatenbank und schnelles Nachschlagewerk.

## 2. Digitale Lernkarten (Active Recall & Spaced Repetition)

- **Methode:** Faktenwissen (BEG-Theorie, Vokabeln, Definitionen) aktiv abrufen, um es ins Langzeitgedächtnis zu verschieben.
- **Umsetzung:** Svelte-Interface mit SQLite-Backend. Der Lernfortschritt wird gespeichert, um Wiederholungen optimal zu takten.

## 3. Multiple Choice (Microlearning)

- **Methode:** Schnelle Wissensüberprüfung über das Wiedererkennen von Antworten (Recognition).
- **Fokus:** Eignet sich **nur** für das Lernen zwischendurch (z.B. unterwegs). Es ersetzt nicht den freien Abruf für die Prüfungen, schließt aber Lücken im Alltag.

## 4. Deep Work (Komplexe Aufgaben & Transfer)

- **Methode:** Echtes Durchrechnen und Anwenden (z.B. KSK-Buchungssätze, Mathe-Kurvendiskussionen).
- **Umsetzung:** Klassisch mit Stift und Papier für die Prüfungsnähe.
- **Ausbau (Optional):** Integration eines dynamischen Aufgaben-Generators im Frontend mit Input-Feld, um Lösungswege direkt am Bildschirm zu validieren.

## 5. Interleaving (Verschachteltes Lernen)

- **Methode:** Themengebiete beim Üben mischen, um den unvorhersehbaren Themenwechsel in der echten Prüfung zu simulieren.
- **Umsetzung:** Der Algorithmus der App mischt standardmäßig Fächer und Themen. Über ein Einstellungsmenü kann temporär auf ein einzelnes Thema fokussiert werden.

## 6. Feynman-Technik

- **Methode:** Komplexe Zusammenhänge in eigenen, simplen Worten erklären, als würde man sie einem Anfänger beibringen.
- **Umsetzung:** Wenn Konzepte aus der Wissensdatenbank unklar sind, zwingt diese Methode dazu, eigene Erklärungslücken aufzudecken.
