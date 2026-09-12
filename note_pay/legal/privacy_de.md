---
title: Datenschutzrichtlinie
---

# Datenschutzerklärung

**Stand:** 2026-09-09 · **In Kraft:** 2026-09-09

## 1. Wer wir sind

NotePay ist eine lokal ausgerichtete Ausgaben-Tracking-Anwendung („die App"). Der für Ihre personenbezogenen Daten Verantwortliche ist **songshangkun** („wir", „uns"), erreichbar unter **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Für Datenschutzfragen, -ersuchen oder -beschwerden kontaktieren Sie uns unter **13808875@qq.com**.

## 2. Die Kurzfassung

- Ihr Hauptbuch liegt **auf Ihrem Gerät**. Wir betreiben kein Kontosystem und keinen Backend-Server, der Ihre Buchhaltungsdaten speichert.
- Wir **verkaufen** Ihre personenbezogenen Daten **nicht** und nutzen sie **nicht** für verhaltensbezogene Werbung.
- Diese Version der App **enthält kein Werbe-SDK und kein Analyse-SDK**.
- Standort, Kamera, Fotobibliothek und Mikrofon sind **optional** und werden nur verwendet, wenn Sie die entsprechende Funktion aufrufen. Wir verfolgen Ihren Standort niemals im Hintergrund.
- Optionale KI-Funktionen können das von Ihnen Getippte, Gesagte oder Fotografierte an eine aggregierende Drittanbieter-LLM-Plattform senden, die vom Entwickler für Ihre Region vorkonfiguriert ist — siehe Abschnitt 4. Sie konfigurieren diese Adresse oder diesen Schlüssel selbst nicht und können es auch nicht. Sie können dies deaktivieren.

## 3. Informationen, die wir verarbeiten

Da die App lokal ausgerichtet ist, verlässt die meiste Information niemals Ihr Gerät.

### 3.1 Auf Ihrem Gerät gespeicherte Informationen

| Was | Warum | Wo es verbleibt |
|---|---|---|
| Einträge: Betrag, Kategorie, Notiz, Datum, Ortsname | Zur Anzeige Ihres Hauptbuchs, Ihrer Statistiken und Budgets | Datenbank auf dem Gerät |
| Von Ihnen erstellte Hauptbücher und Kategorien | Zur Organisation Ihrer Aufzeichnungen | Datenbank auf dem Gerät |
| App-Einstellungen, einschließlich Sprache und Region | Zur Speicherung Ihrer Präferenzen | Geräteeinstellungen |
| Erinnerungszeitpläne | Zur Benachrichtigung zum von Ihnen festgelegten Zeitpunkt | Datenbank auf dem Gerät und lokale Benachrichtigungen |
| KI-Anbieterschlüssel (vom Entwickler je Region vorkonfiguriert) | Zum Aufruf der von Ihnen aktivierten KI-Funktionen | Auf dem Gerät, **verschlüsselt**; wir können ihn nicht lesen |

Wir halten keine serverseitige Kopie der obigen Daten vor und können sie für Sie nicht wiederherstellen. Bitte erstellen Sie eigene Sicherungskopien.

### 3.2 Nur bei Nutzung einer bestimmten Funktion verarbeitete Informationen

- **Standort (optional).** Wenn Sie einem Datensatz einen Ort zuordnen, liest die App Ihre Koordinaten aus, um einen Ortsnamen aufzulösen. Die Auflösung erfolgt in Festlandchina durch AMap (Gaode) und in anderen Regionen durch Google Maps, abhängig von Ihrer konfigurierten Region. Wir fordern den Standort **nur an, während Sie die App nutzen** — **niemals im Hintergrund**. Sie können die Berechtigung verweigern oder die Kartenfunktion vollständig deaktivieren; der Rest der App funktioniert weiterhin.
- **Kamera und Fotobibliothek (optional).** Wenn Sie einen Beleg fotografieren oder auswählen, wird das Bild zur Erkennung gelesen. Originale werden nicht auf einen unserer Server hochgeladen.
- **Mikrofon (optional).** Bei der Spracheingabe wird Audio aufgenommen und transkribiert. Die Transkription erfolgt **auf Ihrem Gerät** mithilfe von Offline-Sprachmodellen, die Sie herunterladen; das Audio wird nicht an unsere Server übertragen.

### 3.3 Informationen, die Ihr Gerät verlassen

Nur in folgenden Fällen:

1. **Reverse Geocoding** — die von Ihnen ausgewählten Koordinaten werden an AMap oder Google Maps gesendet, um einen Ortsnamen zu erhalten.
2. **KI-Verarbeitung** — wenn Sie die Remote-KI aktivieren, werden der von Ihnen übermittelte Text, das Transkript oder das Belegbild an eine **aggregierende Drittanbieter-LLM-Plattform** gesendet, die vom Entwickler für Ihre Region vorkonfiguriert ist. Diese Plattform wählt für jede Anfrage das Modell, das sie verwendet (das Modell ist nicht von NotePay festgelegt und kann variieren). Der Anbieter verarbeitet den Inhalt unter seiner eigenen Datenschutzerklärung. Sie konfigurieren diese Adresse oder diesen Schlüssel selbst nicht und können es auch nicht.
3. **Kaufnachweis** — In-App-Käufe werden von Apple oder Google verifiziert. Wir erhalten lediglich eine Kaufbestätigung, niemals Ihre Zahlungskartendaten.
4. **Remote-Konfiguration und Modell-Downloads** — die App ruft Konfigurationsdateien, Sprachmodelle und — sofern zutreffend — aktualisierte Rechtsdokumente ab. Diese Anfragen enthalten keinen Inhalt Ihres Hauptbuchs.

Wir betreiben keine Werbe- oder Analyse-SDKs, sodass keine Kennung mit Werbenetzwerken geteilt wird.

## 4. KI-Funktionen, einfach erklärt

Die App kann KI entweder **auf Ihrem Gerät** oder über einen **aggregierende Drittanbieter-LLM-Plattform** ausführen.

- **Gerätemodus:** Ihr Inhalt verbleibt auf Ihrem Gerät. Es wird nichts übertragen.
- **Remote-Modus:** Ihr Inhalt wird an eine für Ihre Region ausgewählte **aggregierende Drittanbieter-LLM-Plattform** übertragen. Diese Plattform kann sich außerhalb Ihres Landes befinden und wählt für jede Anfrage selbst das Modell, das sie aufruft — das konkrete Modell wird nicht von NotePay bestimmt und kann von Anfrage zu Anfrage variieren. Die Plattform verarbeitet Ihren Inhalt unter ihrer eigenen Datenschutzerklärung und kann ihn nach ihren eigenen Aufbewahrungsregeln speichern; bitte lesen Sie deren Richtlinie. **NotePay selbst betreibt keinen Server, behält keine Kopie Ihres Inhalts und protokolliert nichts von dem, was Sie übermitteln.** Übermitteln Sie im Remote-Modus keine Informationen, die Sie für vertraulich halten.

Sie können jederzeit in den Gerätemodus wechseln oder die Nutzung von KI-Funktionen in den Einstellungen beenden.

## 5. Warum wir Ihre Informationen verarbeiten

Wir verarbeiten Informationen nur, um: Ihre Ausgaben aufzuzeichnen und anzuzeigen; Statistiken, Budgets und Erinnerungen zu erstellen; Ortsnamen aufzulösen; Belege und Sprache auf Ihren Wunsch zu erkennen; Käufe zu verifizieren; sowie die App funktionsfähig und sicher zu halten.

Wir nutzen den Inhalt Ihres Hauptbuchs nicht, um Modelle zu trainieren, ein Profil über Sie zu erstellen oder Werbung zielgerichtet auszuspielen.

## 6. Dritte, die Informationen erhalten können

| Empfänger | Was empfangen wird | Zweck |
|---|---|---|
| AMap (Gaode) — Region Festlandchina | Von Ihnen ausgewählte Koordinaten | Reverse Geocoding |
| Google Maps — andere Regionen | Von Ihnen ausgewählte Koordinaten | Reverse Geocoding |
| Die für Ihre Region vom Entwickler vorkonfigurierte aggregierende Drittanbieter-LLM-Plattform | Von Ihnen übermittelter Text, Transkript oder Bild | Von Ihnen angeforderte KI-Verarbeitung |
| Apple App Store / Google Play | Kauf-Token | Kaufverifizierung |

Jeder Empfänger unterliegt seiner eigenen Datenschutzerklärung. Wir verkaufen oder vermieten personenbezogene Daten an niemanden.

## 7. Wie lange wir Informationen aufbewahren

Ihr Hauptbuch und Ihre Einstellungen verbleiben auf Ihrem Gerät, bis Sie den Datensatz löschen, die Daten löschen oder die App deinstallieren. Das Löschen oder Deinstallieren entfernt sie dauerhaft; wir halten keine Kopie vor und können sie nicht wiederherstellen.

An einen Remote-aggregierende Drittanbieter-LLM-Plattform übermittelte Inhalte werden gemäß der Speicherdauer dieses Anbieters aufbewahrt.

## 8. Sicherheit

Ihre Daten werden in einer lokalen Datenbank gespeichert, die durch die eigene Sicherheit Ihres Geräts geschützt ist (Geräte-Passcode, Festplattenverschlüsselung). Ihr KI-Anbieterschlüssel, sofern vorhanden, wird verschlüsselt auf dem Gerät gespeichert und niemals an uns übertragen. Keine Speichermethode ist vollkommen sicher, bitte schützen Sie Ihr Gerät und halten Sie Sicherungskopien vor.

## 9. Kinder

Die App richtet sich nicht an Kinder. Wir erfassen wissentlich keine personenbezogenen Daten von Kindern unter dem Alter der digitalen Einwilligungsfähigkeit in ihrer Rechtsordnung (13 in den Vereinigten Staaten, 16 in weiten Teilen des EWR sowie wie örtlich andernorts definiert). Wenn Sie glauben, dass ein Kind uns Informationen übermittelt hat, kontaktieren Sie uns; wir helfen, diese zu entfernen.

## 10. Ihre Rechte

Ihre Rechte hängen davon ab, wo Sie wohnen; der unten gezeigte regionsspezifische Abschnitt erläutert sie im Detail. Unabhängig von Ihrem Wohnort können Sie jederzeit: optionale Berechtigungen verweigern oder widerrufen; Ihre Daten aus der App exportieren oder löschen; die Nutzung von KI-Funktionen beenden; oder sich mit einem Ersuchen an uns wenden.

Da Ihre Daten lokal vorliegen, ist der schnellste Weg, Auskunft, Berichtigung, Übertragbarkeit oder Löschung auszuüben, direkt in der App.

## 11. Änderungen dieser Richtlinie

Wir können diese Richtlinie aktualisieren. Wenn wir dies tun, ändern wir das Datum oben und benachrichtigen Sie bei wesentlichen Änderungen in der App. Die weitere Nutzung der App nach einer Aktualisierung bedeutet, dass Sie die überarbeitete Richtlinie akzeptieren.

## 12. Kontakt

Datenschutzfragen und -ersuchen: **13808875@qq.com**
Postanschrift: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**

