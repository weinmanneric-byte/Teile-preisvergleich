🔧 Teile-Preisvergleich (STAkis + TEXKAT)
Eine interaktive Streamlit-Anwendung zum Vergleichen von Artikelnummern und Preisen aus Exporte-Dateien (CSV/Excel) von STAkis und TEXKAT.
🚀 Funktionen
￼ Datei-Upload: Unterstützt CSV, XLSX und XLS-Dateien.
￼ Automatische Spaltenerkennung: Erkennt meist automatisch die Spalten für Artikelnummern und Preise.
￼ Datenbereinigung:
￼ Normalisiert Artikelnummern (entfernt Leerzeichen, Bindestriche, Punkte, etc.).
￼ Bereinigt Preisformate (Komma/Punkt-Konvertierung, Währungssymbole).
￼ Preisvergleich:
￼ Berechnet absolute (€) und prozentuale (%) Preisdifferenzen.
￼ Kennzeichnet, welche Quelle günstiger ist.
￼ Filter & Optionen:
￼ Nur gemeinsame Artikel anzeigen.
￼ Nur Artikel mit Preisunterschied anzeigen.
￼ Mindestdifferenz-Filter anwenden.
￼ Excel-Export: Laden der Ergebnisse als strukturierte Excel-Datei inklusive separater Tabellenblätter für exklusive Artikel.
🛠️ Installation & Lokaler Start
1. Repository klonen oder Dateien herunterladen
Stelle sicher, dass folgende Dateien im selben Ordner liegen:
￼ ⁠app.py⁠
￼ ⁠requirements.txt⁠
￼ ⁠README.md⁠
2. Abhängigkeiten installieren
Öffne das Terminal/die Eingabeaufforderung im Projektordner und führe folgenden Befehl aus:
3. Anwendung starten
Starte die Streamlit-App mit:
Die Anwendung öffnet sich anschließend automatisch in deinem Browser unter ⁠http://localhost:8501⁠.
💡 Nutzungshinweise
1. Dateien exportieren: Exportiere die Teilelisten aus STAkis und TEXKAT als CSV oder Excel.
2. Hochladen: Lade in der App unter Quelle A die STAkis-Datei(en) und unter Quelle B die TEXKAT-Datei(en) hoch.
3. Spalten anpassen: Falls die automatische Erkennung die Spalten nicht korrekt zuordnet, passe sie manuell in den Dropdown-Menüs an.
4. Ergebnisse filtern & exportieren: Nutzen Sie die Filter in der linken Seitenleiste und laden Sie den fertigen Vergleich bei Bedarf als Excel-Datei herunter.
