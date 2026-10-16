# BLACKOUT 2049 – Mathe-Escape-Game

**Erstellt von Jutta Aeckersberg mit ChatGPT**

Interaktives Escape-Lernspiel für Schülerinnen und Schüler von etwa 16 bis 18 Jahren. Sie erschließen sich drei Verfahren zum Lösen linearer Gleichungssysteme mit zwei Unbekannten: Gleichsetzen, Einsetzen sowie Addieren/Subtrahieren einschließlich des Multiplizierens ganzer Gleichungen.

## Spielablauf

Ausgangspunkt ist die Stadtkarte von NOVA. Die Spielenden lösen drei Missionen: Energiezentrale, Funknetz und Kontrollzentrum. Jede Mission enthält die Erarbeitung des Verfahrens, angeleitete Erprobung, drei reguläre Einsatzaufgaben und ein großes Expertenfinale. Nach erfolgreicher Expertenberechnung wird der Schnittpunkt der beiden Geraden als graphische Bestätigung angezeigt.

Die Stadtkarte wird mit jedem Erfolg heller. Nach dem letzten Expertencode ist NOVA vollständig beleuchtet.

Die Spielenden können die Aufgaben in Ruhe bearbeiten, ohne Countdown. Für Fehlversuche gibt es keinen Punktabzug. Bei der Erarbeitung sind Hilfen ohne Abzug verfügbar. In den bewerteten Aufgaben sind bis zu drei gestufte Hilfen vorgesehen; auch bei Nutzung aller Hilfen sind noch positive Zeitpunkte möglich. Insgesamt sind höchstens **145 Zeitpunkte** erreichbar, davon 120 in regulären Einsätzen und 25 in den Expertenfinals. Mit allen Hilfen und korrekter Lösung sämtlicher Aufgaben bleiben **106 Zeitpunkte** möglich.

## Nutzung ohne Installation

Die Datei `index.html` kann per Doppelklick im Browser gestartet werden. Sie arbeitet grundsätzlich ohne Internet. Nur die verlinkten Lizenzseiten werden beim Öffnen über das Internet aufgerufen.

### Bereitstellung mit GitHub Pages

1. Ein GitHub-Repository erstellen.
2. `index.html`, `LICENSE.md`, `LICENSE_CODE.txt` und diese `README.md` in die oberste Verzeichnisebene hochladen.
3. Im Repository unter **Settings → Pages** die Veröffentlichung aus dem Branch wählen (gewöhnlich `main`, Verzeichnis `/root`).
4. Den anschließend angezeigten GitHub-Pages-Link mit den Lernenden teilen.

Das Spiel braucht keinen Server zum Übermitteln oder Speichern von Nutzerdaten. Es sendet auch keine Punktestände an die Lehrkraft. Der Fortschritt bleibt in der aktuellen Browsersitzung und kann zusätzlich über eine JSON-Sicherungsdatei gespeichert und später wieder eingelesen werden. Eine Sicherung vor dem Schließen ist empfehlenswert.

**Bestehende Spielstände:** Sicherungen aus der vorherigen vollständigen Version 7 lassen sich grundsätzlich einlesen. Da neue Zwischenschritte und Expertenfinals hinzugekommen sind, kann insbesondere ein bereits bearbeitetes Kontrollzentrum erneut zu durchlaufen sein. Bitte die alte Datei als zusätzliche Sicherung behalten.

## Lizenz

**Die kreative Ausgestaltung des Escape-Games** – insbesondere die konkrete Story, das didaktisch gestaltete Spielerlebnis, eigens formulierte Lerntexte, Dialoge und die konkrete Spielgestaltung – steht, soweit schutzfähig, unter **CC BY-NC-SA 4.0** (Namensnennung, nichtkommerziell, Weitergabe unter gleichen Bedingungen). Der funktionale Programmcode wird unter **MIT** bereitgestellt. Weitere Hinweise und Geltungsbereiche stehen in `LICENSE.md` und `LICENSE_CODE.txt`.

Die nichtkommerzielle Creative-Commons-Lizenz gilt nur für die genannten kreativen Spielbestandteile. Der technische Quellcode unter MIT darf separat auch kommerziell genutzt werden.

## Ergebnissicherung als PDF

Nach jeder vollständig abgeschlossenen Mission können die Lernenden die vollständigen Rechenwege als PDF sichern. Nach Abschluss aller drei Missionen erscheint zusätzlich eine gemeinsame Ergebnissicherung mit dem Titel „Lösen von linearen Gleichungssystemen mit 2 Unbekannten“. Sie enthält die Musterlösungen aller Missionen, die Verfahrensnamen, die Proben und die graphischen Expertenkontrollen.

Dazu im Spiel auf „Als PDF speichern“ klicken und im Druckdialog des Browsers „Als PDF speichern“ als Ziel auswählen. Diese Funktion benötigt keine Internetverbindung und übermittelt keine Daten. Die Sicherungsdatei für den Spielstand (JSON) ist davon unabhängig.


PDF-Seitenzahlen: Die Ergebnissicherung enthaelt auf jeder Seite die Nummerierung "Seite X von Y". Sie wird beim Speichern als PDF automatisch mit ausgegeben, auch bei einzelnen Missionen. Im Druckdialog moeglichst A4 und 100 % Skalierung waehlen.
