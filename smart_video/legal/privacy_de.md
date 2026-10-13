---
title: Datenschutzrichtlinie
---

# Datenschutzrichtlinie

**Zuletzt aktualisiert:** 2026-10-09 · **In Kraft:** 2026-10-09

## 1\. Wer wir sind

Smart Video ist ein lokal ausgerichteter intelligenter Medienplayer für Sprachlernende („die App"). Die für Ihre personenbezogenen Daten verantwortliche Stelle ist **songshangkun** („wir", „uns"), erreichbar unter **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Für datenschutzbezogene Fragen, Anträge oder Beschwerden kontaktieren Sie uns unter **13808875@qq.com**.

## 2\. Die kurze Fassung

  * Ihre Mediathek, Untertitel, Notizen und Lernaufzeichnungen befinden sich **auf Ihrem Gerät**. Wir betreiben kein Kontosystem und keinen Server, der Ihre Lernedaten speichert.
  * Wir **verkaufen** Ihre personenbezogenen Daten **nicht** und **verwenden** sie nicht für verhaltensbasierte Werbung.
  * Diese Version der App **enthält kein Werbe-SDK und kein Analyse-SDK**.
  * Der Zugriff auf die Fotobibliothek und Dateien ist **freiwillig** und wird nur beim Import oder Export von Medien genutzt. Wir greifen niemals auf die Kamera, das Mikrofon oder Ihren Standort zu.
  * KI-Funktionen senden den von Ihnen ausgewählten Text an einen **von Ihnen selbst konfigurierten LLM-Endpunkt** — siehe Abschnitt 4. Die sprachliche Erkennung auf dem Gerät verlässt Ihr Gerät niemals.



## 3\. Informationen, die wir verarbeiten

Da die App lokal ausgerichtet ist, verlässt die meiste Information Ihr Gerät niemals.

### 3.1 Auf Ihrem Gerät gespeicherte Informationen

Was | Warum | Wo sie verbleibt  
---|---|---  
Einträge der Mediathek: Dateiverweise, Namen, importierte URLs / HLS-Links, Wiedergabeposition | Damit Sie Ihre Lernmedien erneut öffnen und fortsetzen können | Lokale Datenbank (App-Sandbox)  
Untertiteldateien und Transkriptions-Zwischenspeicher | Zum Anzeigen von Untertiteln und Aktivieren der Wortabfrage | Lokale Datenbank  
Zwischenspeicher für KI-Erklärungen & -Zusammenfassungen (Wörter, Sätze, Medienzusammenfassungen) | Zum Anzeigen früherer Ergebnisse ohne erneuten KI-Aufruf | Lokale Datenbank  
Lernaufzeichnungen zu Wörtern / Lernkarten und Wiederholungspläne | Zum Antreiben der Wiederholung mit verteilten Abständen | Lokale Datenbank  
Von Ihnen erstellte Notizen | Zum Aufbewahren Ihrer Lernnotizen | Auf dem Gerät (Speicher / lokaler Speicher)  
App-Einstellungen, einschließlich Design, Sprache und Untertitelstil | Zum Merken Ihrer Voreinstellungen | Lokale Einstellungen  
LLM-Endpunkt-Adresse und -Schlüssel, sofern Sie einen konfigurieren | Zum Aufrufen der von Ihnen aktivierten KI-Funktionen | Auf dem Gerät, **verschlüsselt** ; wir können ihn nicht lesen  
  
Wir halten keine serverseitige Kopie der obigen Daten und können sie für Sie nicht wiederherstellen. Bitte erstellen Sie eigene Sicherungen.

### 3.2 Informationen, die nur bei Nutzung einer bestimmten Funktion verarbeitet werden

  * **Fotobibliothek (freiwillig).** Beim Import von Medien liest die App die von Ihnen ausgewählten Videos / Audiodateien aus Ihrer Fotobibliothek. Beim Export von Lernmaterial schreibt die App in Ihre Fotobibliothek. Wir durchsuchen Ihre Bibliothek niemals im Hintergrund. Sie können die Berechtigung verweigern; der Rest der App funktioniert weiterhin.
  * **Dateien / Dokumente (freiwillig).** Beim Import lokaler Medien oder Dokumente liest die App die von Ihnen in der Dateien-App / „Auf meinem iPhone" ausgewählten Dateien. Es wird nichts auf einen von uns betriebenen Server hochgeladen.
  * **Kein Mikrofon, keine Kamera, kein Standort.** Smart Video fordert das Mikrofon, die Kamera oder Standortdienste nicht an und nutzt sie nicht. Die Spracherkennung erfolgt auf Audio, _das sich bereits in Ihrer importierten Mediendatei befindet_ , mithilfe von Modellen auf dem Gerät — sie nimmt niemals über das Mikrofon auf.



### 3.3 Informationen, die Ihr Gerät verlassen

Nur in diesen Fällen:

  1. **KI-Verarbeitung.** Wenn Sie KI-Funktionen nutzen (Untertitelübersetzung, Wort- & Satzerklärung, Zusammenfassung & Folgefragen), wird der von Ihnen ausgewählte Text an den **von Ihnen selbst in Einstellungen → Modellbibliothek → LLM-Server konfigurierten LLM-Endpunkt** gesendet. Der Empfänger ist der von Ihnen gewählte Anbieter; wir betreiben ihn nicht, können die von Ihnen konfigurierte Adresse oder den Schlüssel nicht lesen und halten keine Kopie dessen, was Sie übermitteln. Bitte prüfen Sie die Datenschutzrichtlinie dieses Anbieters.
  2. **Spracherkennung (auf dem Gerät).** Die Transkription erfolgt lokal mit sherpa-Modellen, die Sie in der Modellbibliothek herunterladen. Audio und Text werden **nicht** irgendwohin gesendet.
  3. **Kaufbestätigung.** In-App-Käufe werden vom App Store auf Ihrem Gerät verifiziert (derzeit der Apple App Store). Wir erhalten nur eine Kaufbestätigung, niemals die Daten Ihrer Zahlungskarte.
  4. **Remote-Konfiguration und Modell-Downloads.** Die App ruft Konfigurationsdateien und auf dem Gerät laufende ASR-Modelle (sherpa) von den GitHub Pages / GitHub des Entwicklers ab. Diese Anfragen enthalten weder Ihre Medien noch Ihre Lerninhalte.



Wir betreiben keine Werbe- oder Analyse-SDKs, daher wird kein Kennzeichen mit Werbenetzwerken geteilt.

## 4\. KI-Funktionen, einfach erklärt

Smart Video bietet zwei Arten der KI-Verarbeitung:

  * **Spracherkennung auf dem Gerät (ASR):** Die Transkription erfolgt auf Ihrem Gerät mit einem von Ihnen heruntergeladenen sherpa-Modell. **Ihr Audio und Text verlassen Ihr Gerät niemals — es wird nichts übertragen.**
  * **Von Ihnen konfigurierter LLM-Endpunkt (BYOK):** Übersetzung, Erklärung und Zusammenfassung werden erzeugt, indem der ausgewählte Text an die **von Ihnen selbst in Einstellungen → Modellbibliothek → LLM-Server eingegebene LLM-Adresse und den Schlüssel** gesendet wird. Der Anbieter wird von Ihnen gewählt — wir betreiben ihn weder, noch können wir die von Ihnen konfigurierte Adresse oder den Schlüssel lesen. Bitte prüfen Sie die Datenschutz- und Aufbewahrungsrichtlinie dieses Anbieters und übermitteln Sie über diesen Kanal keine Informationen, die Sie für vertraulich halten.



Sie können KI-Funktionen jederzeit in den Einstellungen deaktivieren; der Player, die Untertitel und die lokalen Lernwerkzeuge funktionieren ohne KI weiter.

## 5\. Warum wir Ihre Informationen verarbeiten

Wir verarbeiten Informationen nur, um: Ihre Medien zu importieren und abzuspielen; Untertitel anzuzeigen und die Wortabfrage zu ermöglichen; die von Ihnen angeforderte Transkription auf dem Gerät auszuführen; den von Ihnen konfigurierten KI-Endpunkt aufzurufen; Käufe zu verifizieren; und die App funktionsfähig und sicher zu halten.

Wir verwenden Ihre Lerninhalte nicht, um Modelle zu trainieren, ein Profil von Ihnen zu erstellen oder Werbung zu schalten.

## 6\. Dritte, die möglicherweise Informationen erhalten

Empfänger | Was empfangen wird | Zweck  
---|---|---  
Der von Ihnen selbst konfigurierte LLM-Anbieter | Der von Ihnen zur Übersetzung / Erklärung / Zusammenfassung übermittelte Text | Von Ihnen angeforderte KI-Verarbeitung  
Apple App Store | Kauftoken | Kaufbestätigung  
GitHub Pages / GitHub (Entwickler) | Konfigurations- & Modell-Download-Anfragen (keine Medieninhalte) | Remote-Konfiguration und Bereitstellung des ASR-Modells auf dem Gerät  
  
Jeder Empfänger unterliegt seiner eigenen Datenschutzrichtlinie. Wir verkaufen oder vermieten personenbezogene Daten an niemanden.

## 7\. Wie lange wir Informationen aufbewahren

Ihre Mediathek, Untertitel, Notizen und Lernaufzeichnungen verbleiben auf Ihrem Gerät, bis Sie sie löschen, die Daten zurücksetzen oder die App deinstallieren. Das Löschen oder Deinstallieren entfernt sie dauerhaft; wir halten keine Kopie und können sie nicht wiederherstellen.

Inhalte, die Sie an Ihren konfigurierten LLM-Anbieter übermitteln, werden gemäß der Aufbewahrungsrichtlinie dieses Anbieters aufbewahrt.

## 8\. Sicherheit

Ihre Daten werden in einer lokalen Datenbank gespeichert, die durch die Sicherheit Ihres Geräts selbst geschützt ist (Geräte-Passcode, Festplattenverschlüsselung). Die LLM-Endpunkt-Adresse und der Schlüssel werden verschlüsselt auf dem Gerät gespeichert und niemals an uns übertragen. Keine Speichermethode ist vollkommen sicher, daher schützen Sie bitte Ihr Gerät und erstellen Sicherungen.

## 9\. Kinder

Die App richtet sich nicht an Kinder. Wir erfassen wissentlich keine personenbezogenen Daten von Kindern unter dem Alter der digitalen Einwilligung in ihrer Rechtsordnung (13 in den Vereinigten Staaten, 16 in weiten Teilen des EWR und wie lokal andernorts definiert). Wenn Sie glauben, dass ein Kind uns Informationen übermittelt hat, kontaktieren Sie uns, und wir helfen beim Entfernen.

## 10\. Ihre Rechte

Ihre Rechte hängen davon ab, wo Sie wohnen; der unten in diesem Dokument gezeigte regionsspezifische Abschnitt erläutert sie im Detail. Unabhängig von Ihrem Wohnort können Sie jederzeit: freiwillige Berechtigungen verweigern oder widerrufen; Ihre Daten aus der App heraus exportieren oder löschen; die Nutzung von KI-Funktionen beenden; oder sich mit einem Antrag an uns wenden.

Da Ihre Daten lokal sind, ist der schnellste Weg, Auskunft, Berichtigung, Übertragbarkeit oder Löschung auszuüben, direkt in der App.

## 11\. Änderungen dieser Richtlinie

Wir können diese Richtlinie aktualisieren. Wenn wir dies tun, ändern wir das obige Datum und informieren Sie bei wesentlichen Änderungen in der App. Die weitere Nutzung der App nach einer Aktualisierung bedeutet, dass Sie die überarbeitete Richtlinie akzeptieren.

## 12\. Kontakt

Datenschutzfragen und -anträge: **13808875@qq.com**  
Postanschrift: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
