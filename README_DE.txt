FAHRZEUGÜBERFÜHRUNG SCHARF – ANDROID-PROJEKT

Dieses Paket enthält den Quellcode zum Erstellen einer installierbaren Test-APK.
Es ist noch keine fertige APK.

Einfachster Build ohne Computer:
1. Erstelle kostenlos ein Konto auf GitHub.com im Browser deines Android-Handys.
2. Erstelle ein neues Repository. Stelle es für private Nutzung ein, wenn verfügbar.
3. Lade die Dateien aus diesem ZIP in das Repository hoch. GitHub im Browser:
   „Add file“ > „Upload files“; lade den Inhalt dieses Ordners hoch (einschließlich .github).
4. Öffne den Tab „Actions“. Falls Workflows noch nicht aktiviert sind, aktiviere sie.
5. Wähle „Build Android APK“ > „Run workflow“.
6. Warte, bis der Workflow grün/erfolgreich ist. Öffne den Lauf und lade das Artefakt
   „Fahrzeugueberfuehrung-Scharf-APK“ herunter.
7. Entpacke das heruntergeladene Artefakt und tippe auf app-debug.apk.
   Android fragt eventuell, ob Chrome/Dateien Apps installieren darf; erlaube es nur,
   wenn du diese APK selbst aus deinem Build heruntergeladen hast.

WICHTIG:
- In der App ist keine Anmeldung eingebaut.
- Das Projekt verpackt den bestehenden Prototyp in eine Android-WebView.
- Galerie-Auswahl wird an Android weitergereicht.
- Daten werden lokal im App-Browser gespeichert.
- Cloud-Synchronisierung ist NICHT implementiert.
- Teste die App mit einem Beispieldatensatz, bevor du echte Kunden-/Fahrzeugdaten nutzt.
