---
title: Datenschutzerklärung
---

# Datenschutzerklärung

**Zuletzt aktualisiert:** 2026-11-08 · **Inkrafttreten:** 2026-11-08

## 1. Wer wir sind

Smart Reader (die „App") ist eine lokal arbeitende Lese- und Lern-App. Verantwortlicher für Ihre personenbezogenen Daten ist **songshangkun** („wir"), erreichbar unter **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Bei Fragen, Anfragen oder Beschwerden zum Datenschutz erreichen Sie uns unter **13808875@qq.com**.

## 2. Kurzfassung

- Ihre Lesebibliothek, importierten Dokumente, Notizen, Zusammenfassungen und Einstellungen befinden sich **auf Ihrem Gerät**. Wir betreiben kein Konto-System und keinen Server, der Ihre Lesedaten speichert.
- Wir **verkaufen** Ihre personenbezogenen Daten **nicht** und nutzen sie **nicht** für verhaltensbezogene Werbung.
- Diese Version der App **enthält kein Werbe-SDK und kein Analyse-SDK** und hat **keine In-App-Käufe**.
- Die App fordert **nur die Mikrofon-Berechtigung** an, und ausschließlich für die optionale Spracheingabe und Notizaufnahmen, die **auf Ihrem Gerät** durch das Streaming-Spracherkennungsmodell transkribiert werden. Audio wird niemals hochgeladen. Kamera-, Fotobibliothek- und Standort-Berechtigungen werden nicht angefordert. Dokumente und Bilder werden ausschließlich über die System-Dateiauswahl importiert; die Texterkennung (OCR) läuft **vollständig auf Ihrem Gerät**.
- KI-Funktionen laufen entweder auf einem **LLM-Endpunkt, den Sie selbst konfigurieren**, oder mit einem **auf Ihr Gerät heruntergeladenen lokalen Modell** – siehe Abschnitt 4.

## 3. Welche Informationen wir verarbeiten

Da die App lokal arbeitet, verlassen nahezu alle Informationen Ihr Gerät nicht.

### 3.1 Auf Ihrem Gerät gespeicherte Informationen

| Inhalt | Zweck | Speicherort |
|---|---|---|
| Importierte Dokumente (PDF, EPUB, Office, Text, Bilder) und ihr extrahierter Text | Öffnen, Umbrechen und erneutes Lesen | App-Sandbox (Application-Support-Verzeichnis) |
| Bibliothekseinträge: Titel, Format, Importzeit, Leseposition | Anzeige der Bibliothek und Fortsetzen an der letzten Stelle | Datenbank auf dem Gerät |
| Lokaler Volltext-/Suchindex und KI-Ergebnis-Cache (Erklärungen, Zusammenfassungen, Fragen & Antworten) | Durchsuchen Ihrer Dokumente und Vermeidung wiederholter KI-Aufrufe | Datenbank und Indexverzeichnis auf dem Gerät |
| Lese- und Darstellungseinstellungen (Design, Sprache, Schrift, Blättermodus, Schnellaktionen) | Speichern Ihrer Einstellungen | Geräteeinstellungen |
| Heruntergeladene Sprachmodelle (TTS) | Offline-Vorlesen von Dokumenten | App-Sandbox (Modellverzeichnis) |
| LLM-Endpunktadresse, Modellname und API-Schlüssel, falls konfiguriert | Aufruf der von Ihnen aktivierten KI-Funktionen | Auf dem Gerät, verschleiert gespeichert; wir können ihn nicht lesen |
| Heruntergeladene Spracherkennungs-(ASR)-, On-Device-LLM- und Embedding-Modelle | Spracheingabe, Offline-Fragen & Antworten und semantische Suche | App-Sandbox (Modellverzeichnis) |
| Notizaufnahmen, Chatverlauf, Zusammenfassungen und geteilte Notizen | Aufnahmen erneut hören und weiterlernen | Datenbank auf dem Gerät und App-Sandbox |

Wir halten keine serverseitige Kopie der oben genannten Daten und können sie nicht für Sie wiederherstellen. Bitte sichern Sie Ihre Daten selbst.

### 3.2 Informationen, die nur bei Nutzung bestimmter Funktionen verarbeitet werden

- **Dateien / Dokumente (optional).** Beim Import eines Dokuments oder Bildes liest die App nur die Dateien, die Sie in der System-Dateiauswahl auswählen. Nichts wird auf einen von uns betriebenen Server hochgeladen.
- **Texterkennung auf dem Gerät (OCR).** Bilder und gescannte PDF-Seiten werden lokal durch die ML-Kit-Texterkennung auf dem Gerät erkannt. Bilder verlassen Ihr Gerät nie.
- **Sprachsynthese auf dem Gerät (TTS).** Dokumente werden von Sprachmodellen vorgelesen, die Sie herunterladen und lokal ausführen. Text wird nirgendwohin gesendet.
- **Spracheingabe und Notizaufnahmen (optional).** Wenn Sie Text diktieren oder eine Aufnahme an eine Notiz anhängen, nutzt die App das Mikrofon und ein Streaming-Spracherkennungsmodell, das **vollständig auf Ihrem Gerät** läuft. Audio wird lokal in Text umgewandelt und nicht hochgeladen. Sie können die Mikrofon-Berechtigung ablehnen; Lesen, KI und andere Funktionen bleiben verfügbar.
- **On-Device-Modelle (optional).** Sie können Spracherkennungs-, Sprachsynthese-, Embedding- und kleine Sprachmodelle (GGUF) herunterladen. Diese Dateien liegen in der App-Sandbox und laufen lokal; Ihr Text und Audio werden nicht an uns oder an einen Modellanbieter gesendet.

### 3.3 Informationen, die Ihr Gerät verlassen

Nur in folgenden Fällen:

1. **KI-Verarbeitung (optional).** Wenn Sie KI-Erklärungen, Zusammenfassungen, Rückfragen oder Schnellaktionen nutzen, wird der von Ihnen markierte Text bzw. der relevante Auszug an den **LLM-Endpunkt gesendet, den Sie selbst** unter Einstellungen → KI-Dienst **konfiguriert haben**. Empfänger ist der von Ihnen gewählte Anbieter; wir betreiben ihn nicht, können die konfigurierte Adresse oder den Schlüssel nicht lesen und bewahren keine Kopie Ihrer Übermittlung auf. Bitte prüfen Sie die Datenschutzerklärung dieses Anbieters.
2. **Remote-Konfiguration und Dokumentbereitstellung.** Die App lädt Konfigurationsdateien, Rechtstexte und die optionale App-Empfehlungsliste von den GitHub Pages des Entwicklers und lädt Sprach-, Spracherkennungs-, Embedding- und lokale Sprachmodelle aus dem Modell-Repository (Hugging Face / hf-mirror). Diese Anfragen enthalten keine Dokumentinhalte, Leseverläufe, Audiodaten oder personenbezogenen Kennungen.
3. **Von Ihnen ausgelöste Netzwerkzugriffe.** Das Öffnen eines Bildes oder Links in einem Dokument überträgt für sich genommen nichts; die App enthält keine Browser-, Tracking- oder Werbekomponenten.

## 4. KI-Funktionen, einfach erklärt

- **Vom Nutzer konfigurierter LLM-Endpunkt (BYOK):** Erklärungen, Zusammenfassungen, Übersetzungen und Fragen & Antworten entstehen durch Senden des markierten Textes an die **LLM-Adresse und den Schlüssel, die Sie selbst eingeben**. Der Anbieter wird von Ihnen gewählt – wir betreiben ihn nicht und können die konfigurierte Adresse oder den Schlüssel nicht lesen. Bitte prüfen Sie die Datenschutz- und Aufbewahrungsrichtlinien dieses Anbieters und übermitteln Sie über diesen Kanal keine vertraulichen Informationen.
- **Lokales LLM-Modell (optional):** Erklärungen, Zusammenfassungen und Fragen & Antworten können auch von einem kleinen GGUF-Modell erzeugt werden, das Sie herunterladen und lokal ausführen. In diesem Modus bleibt der Text auf Ihrem Gerät und wird nirgendwohin gesendet.
- **Verarbeitung auf dem Gerät:** Textextraktion, OCR, Volltext- und semantische Indexierung, Sprachsynthese, Spracherkennung und On-Device-Modellinferenz laufen lokal auf Ihrem Gerät. **Ihre Dokumente, Bilder und Audiodaten werden durch diese Funktionen nicht hochgeladen.**

Sie können KI-Funktionen jederzeit deaktivieren; Lesen, Suche und Offline-Vorlesen funktionieren auch ohne sie.

## 5. Warum wir Ihre Informationen verarbeiten

Wir verarbeiten Informationen ausschließlich, um: Ihre Dokumente zu importieren und anzuzeigen; Text zu extrahieren und umzubrechen; Ihnen Suche, Notizen und Organisation Ihrer Bibliothek zu ermöglichen; die von Ihnen angeforderte OCR und Sprachsynthese auf dem Gerät auszuführen; den von Ihnen konfigurierten KI-Endpunkt aufzurufen; und die App funktionsfähig und sicher zu halten.

Wir nutzen Ihre Dokumente oder Leseverläufe nicht zum Trainieren von Modellen, zur Profilbildung oder für gezielte Werbung.

## 6. Dritte, die Informationen erhalten können

| Empfänger | Erhält | Zweck |
|---|---|---|
| Der von Ihnen konfigurierte LLM-Anbieter | Den für Erklärung, Zusammenfassung oder Fragen & Antworten übermittelten Text | Die von Ihnen angeforderte KI-Verarbeitung |
| GitHub Pages / GitHub (Entwickler) | Anfragen zu Konfiguration, Rechtstexten und App-Empfehlungen (keine Dokumentinhalte) | Remote-Konfiguration, Dokumentbereitstellung und App-Empfehlung |
| Hugging Face / hf-mirror | Anfragen zum Download von Sprach-, Spracherkennungs-, Embedding- und lokalen LLM-Modellen (keine Dokumentinhalte) | Bereitstellung von On-Device-Modellen |

Jeder Empfänger unterliegt seiner eigenen Datenschutzerklärung. Wir verkaufen oder vermieten personenbezogene Daten an niemanden.

## 7. Wie lange wir Informationen aufbewahren

Ihre Dokumente, Indizes, Notizen, KI-Caches und Einstellungen bleiben auf Ihrem Gerät, bis Sie sie löschen, das Dokument aus der Bibliothek entfernen oder die App deinstallieren. Das Löschen eines Dokuments aus der Bibliothek entfernt seinen Eintrag, seine Originaldatei und seine Indexeinträge. Die Deinstallation entfernt alles dauerhaft; wir bewahren keine Kopie auf und können nichts wiederherstellen.

Inhalte, die Sie an Ihren konfigurierten LLM-Anbieter übermitteln, werden nach dessen Aufbewahrungsrichtlinie gespeichert.

## 8. Sicherheit

Ihre Daten liegen in der App-Sandbox und sind durch die Gerätesicherheit (Gerätecode, Datenträgerverschlüsselung) geschützt. Die LLM-Endpunktadresse und der Schlüssel werden auf dem Gerät verschleiert gespeichert und nie an uns übertragen. Keine Speichermethode ist vollkommen sicher; schützen Sie daher Ihr Gerät und erstellen Sie Sicherungen.

## 9. Kinder

Die App richtet sich nicht an Kinder. Wir erheben wissentlich keine personenbezogenen Daten von Kindern unterhalb des digitalen Schutzalters ihrer Jurisdiktion (13 in den USA, 16 in weiten Teilen des EWR, im Übrigen nach lokalem Recht). Wenn Sie glauben, dass ein Kind uns Informationen übermittelt hat, kontaktieren Sie uns – wir helfen beim Löschen.

## 10. Ihre Rechte

Ihre Rechte hängen von Ihrem Wohnort ab. Unabhängig davon können Sie jederzeit: optionale Berechtigungen ablehnen oder widerrufen; Dokumente und ihre Daten in der App löschen; KI-Funktionen nicht mehr nutzen; oder sich mit einer Anfrage an uns wenden.

Da Ihre Daten lokal liegen, ist der schnellste Weg zur Ausübung von Auskunft, Berichtigung, Übertragbarkeit oder Löschung direkt in der App.

## 11. Änderungen dieser Erklärung

Wir können diese Erklärung aktualisieren. In diesem Fall ändern wir das oben genannte Datum und benachrichtigen Sie bei wesentlichen Änderungen in der App. Die weitere Nutzung nach einer Aktualisierung bedeutet, dass Sie die überarbeitete Erklärung akzeptieren.

## 12. Kontakt

Datenschutzfragen und Anfragen: **13808875@qq.com**
Postanschrift: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
