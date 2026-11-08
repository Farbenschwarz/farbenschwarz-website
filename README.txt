FARBENSCHWARZ.CH – STARTSEITE 1.0
================================

Dies ist eine vorläufige, eigenständige One-Page-Website. Kein Webhosting-Abo und keine zusätzlichen Frameworks erforderlich.

DATEIEN
- index.html   Vollständige Website mit Stil, Mobilansicht und 3 versteckten Gags
- favicon.svg  Kleines Symbol für Browser-Tabs

SO ANSEHEN
1. index.html auf einem Computer per Doppelklick in einem Browser öffnen.
2. Auf einem Smartphone kann das lokale Öffnen je nach Gerät schwieriger sein;
   nach dem GitHub-Pages-Upload ist die Seite regulär im Browser erreichbar.

SO AUF GITHUB PAGES VERÖFFENTLICHEN
1. Auf github.com kostenloses Konto anlegen bzw. anmelden.
2. Ein neues Repository mit dem Namen "farbenschwarz-website" erstellen.
   Wichtig: PUBLIC wählen (GitHub Pages ist bei Free für öffentliche Repos verfügbar).
3. Im Repository auf "Add file" > "Upload files" klicken.
4. index.html und favicon.svg hochladen, danach "Commit changes".
5. Unter Settings > Pages > Build and deployment:
   Source = "Deploy from a branch", Branch = "main", Ordner = "/ (root)".
6. Speichern. Danach ist eine Vorschau erreichbar unter:
   https://DEIN-GITHUB-NAME.github.io/farbenschwarz-website/

EIGENE DOMAIN VERBINDEN – ERST WENN DIE GITHUB-SEITE FUNKTIONIERT
1. In GitHub: Repository > Settings > Pages > Custom domain.
   Dort "farbenschwarz.ch" eintragen und speichern.
2. Bei Hostpoint: https://admin.hostpoint.ch/ > Domains > DNS-Zone bearbeiten.
   A-Records für die Hauptdomain (Name leer) mit diesen vier Werten setzen:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   Bestehende konkurrierende A-/AAAA-Einträge für die Hauptdomain müssen
   geprüft/angepasst werden. Mail-Einträge (MX/SPF/TXT) nicht pauschal löschen.
3. Optional für www.farbenschwarz.ch:
   CNAME-Record mit Name "www" und Ziel "DEIN-GITHUB-NAME.github.io".
4. Änderungen bei Hostpoint bestätigen ("Jetzt ausführen").
5. In GitHub > Settings > Pages nach der DNS-Umstellung "Enforce HTTPS" aktivieren,
   sobald verfügbar. Die DNS-Aktualisierung kann bis zu 24 Stunden dauern.

WICHTIG ZU DEN INHALTEN
- Die Cover sind EIGENSTÄNDIGE typografische Platzhalter und keine Originalcover.
- Die Plattform-Links öffnen vorerst Suchergebnisse, keine bestätigten Künstlerprofile.
- Die angekündigte Single "s'Häidi" ist vorsorglich noch als angekündigt markiert.
- Die Jahreszahl 2027 beim Album ist als Planung zu verstehen, nicht als verbindlicher Termin.
- Kontaktdaten fehlen absichtlich, um keine private oder falsche Adresse zu veröffentlichen.

SPÄTER VERBESSERN
- Originalcover und Pudel-Logo integrieren
- Echte Spotify-/Apple-Music-/YouTube-Artist-URLs ersetzen
- Status von s'Häidi nach Veröffentlichung aktualisieren
- Kurze echte Biografie ergänzen
- Impressum / Datenschutzangaben für die öffentliche Website prüfen
- Eventuell später auf eine umfangreiche CMS-Seite migrieren

Dokumentation:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
https://support.hostpoint.ch/de/technisches/dns/dns-aenderungen/dns-zone-manuell-bearbeiten
