<p align="center">
  <img src="https://comniemeer.de/projects/8bitbinder/downloads/Banner.png" alt="8 Bit Binder Banner"/>
</p>

# 8 Bit Binder by Martin [1.1.4]
## Funktionen
### Einstellungen
Die Einstellungen sollten recht selbsterklärend sein.
Zusätzlich findet man weitere Informationen zu allen Einstellungen im Einstellungs-GUI unter "Informationen" (oben in der Menüleiste).
Dort finden sich auch alle Platzhalter, die bei Kill- und Todessprüchen verwendet werden können.

### Hotkeys und eigene Hotkeys
Die Hotkeys wurden minimal gehalten, da nur die wichtigsten Funktionen vom Keybinder vorgegeben sein sollten.
Das Hauptaugenmerk wurde bei dem Keybinder auf eigene Hotkeys gelegt. Dazu stehen 48 Felder zur Verfügung!
Auch bei den Hotkeys und den eigenen Hotkeys sind die wichtigsten Informationen unter "Informationen" in der Menüleiste zu finden.
Bei den eigenen Hotkeys finden sich weitere Platzhalter, die verwendet werden können, und wie sie funktionieren.
Beim ersten Ausführen werden einige Standard-Befehle als eigene Hotkeys definiert - diese können selbstverstänlich angepasst werden!

### Standard-Belegungen der Hotkeys
| Standardbelegung | Beschreibung |
| ---------------- | ------------ |
| M | Motor starten |
| J | Job ausführen |
| - | Statistik anzeigen |
| . | Tempomat starten/stoppen |
| F1 | Ausrüstungsprofil 1 |
| F2 | Ausrüstungsprofil 2 |
| F3 | Ausrüstungsprofil 3 |
| R | Store ausrauben bzw. den nächsten freien Store anzeigen |
| STRG+R | Dialog mit den Stores anzeigen |
| Ä | Letzte Eingabe wiederholen |
| < | Automatische Systeme (/cd, /af, /asp) beenden |
| ALT+Pause | Keybinder pausieren |

### Overlay
Der Keybinder bietet außerdem ein Overlay, welches unter "Einstellungen" -> "Overlay" angepasst werden kann.
Das komplette Erscheinungsbild kann selbstständig angepasst werden, dazu können wieder verschiedene Platzhalter im Textfeld verwendet werden.
Die Platzhalter finden sich wieder oben in der Menüleiste unter "Informationen".
Möchte man Farben verwenden, kann man die Platzhalter [primcol] und [seccol] für die in den Einstellungen definierten Farben verwenden.
Außerdem steht [white] für weiß zur Verfügung. Andere, individuelle Farben können mit {Hex-Farbcode} verwendet werden, z.B. {FF4400}.

Außerdem gibt es ein Gegner-Overlay, welches automatisch alle Spieler gegnerischer Fraktionen ausliest und Ingame anzeigt, wer online ist!

### Befehle
Folgende Befehle sind im Keybinder eingebaut:

| Befehl | Alias | Beschreibung |
| ----------- | -------------------- | --- |
| /kills | /tode, /deaths, /kd | Zeigt die Kills, Tode und die K/D an (Gesamt und Tag) |
| /setkills | /settode, /setdeaths | Liest die Kills und Tode automatisch aus den Statistiken aus |
| /sanis | - | Zeigt die Sanitäter in einem Dialog an |
| /onsanis | - | Zeigt die Sanitäter, die online sind, im Chat an |
| /tempo | - | Stellt das Tempo für den Tempomat ein |
| /ov | /overlay | Aktiviert das Overlay |
| /ovmove | - | Zum Verschieben des Overlays, nach Aktivierung kann man die Pfeiltasten benutzen |
| /ovsave | - | Zum Speichern der Overlay-Position nach dem Verschieben |
| /setjob | - | Zum Setzen des aktuellen Jobs (Drogendealer, Waffendealer, Busfahrer, Pilot, Hochseefischer, Anwalt, Detektiv, Trucker, Farmer) |
| /setline | /setlinie | Zum Setzen der gewünschten Busfahrer-Linie |
| /wskill | /wdskill | Zum Setzen des Waffendealer-Skills |
| /dskill | - | Zum Setzen des Detektiv-Skills |
| /drugstatus | - | Zum Ändern des Drogen-Status (Pflanzen bzw. Ernten) bei Bugs |
| /l1 - /l21 | - | Zum Starten der angegebenen Linie |
| /pd | /payday | Zeigt das errechnete Geld, welches man am nächsten Payday erhält |
| /resetpd | /resetpayday | Setzt das Geld, welches man am nächsten Payday bekommen würde, zurück auf 0$ |
| /settax | - | Zum Einstellen des Steuersatzes |
| /cd | - | Zum Starten eines Countdowns |
| /af | /afind | Zum automatischen Finden eines Spielers |
| /as | /asp | Zum automatischen Zeigen eines Spielers |
| /cfind | /ffind | Zum Suchen eines Spielers mit Durchsagen in dem angegebenen Chat (z.B. Fraktionschat) |
| /wo | - | `/f Wo befindet ihr euch und was ist das Problem?` |
| /cwo | - | `/crew Wo befindet ihr euch und was ist das Problem?` |
| /ver | - | `/f Verstanden und bestätigt!` |
| /cver | - | `/crew Verstanden und bestätigt!` |
| /needbk | - | `/f Wird Verstärkung weiterhin benötigt?` |
| /cneedbk | - | `/crew Wird Verstärkung weiterhin benötigt?` |
| /go | - | `/f Einsatzleiter erlaubt Zugriff, GOGOGO!` |
| /cgo | - | `/crew Einsatzleiter erlaubt Zugriff, GOGOGO!` |
| /abholung | - | `/f Erbitte Abholung in [...]!` |
| /cabholung | - | `/crew Erbitte Abholung in [...]!` |
| /kabholung | - | `/f Eine Abholung wird nicht mehr benötigt.` |
| /ckabholung | - | `/f /crew Eine Abholung wird nicht mehr benötigt.` |
| /verf | /verfolgung | `/f Erbitte Unterstützung bei der Verfolgung von [...]!` |
| /cverf | /cverfolgung | `/crew Erbitte Unterstützung bei der Verfolgung von [...]!` |
| /ort | - | `/f Letzter bekannter Aufenthaltsort: [...]` |
| /cort | - | `/crew Letzter bekannter Aufenthaltsort: [...]` |
| /afish | - | Zum automatischen Fischen |
| /asell | - | Zum automatischen Verkaufen der Fische |
| /acook | - | Zum automatischen Kochen der Fische |
| /fische | - | Zeigt den Wert der geangelten Fische an |
| /hp | - | Zeigt die HP der gekochten Fische an |
| /gf | /gfs | Kurzbefehl für /gangfights, zeigt außerdem die vorhandenen Gangfight-Gebiete an |
| /hdf | /ruhe | Sein Sie bitte still. |
| /afk | - | Zum AFK melden |
| /alotto | - | Zum Kaufen eines Lottotickets (wie in den Einstellungen definiert) |
| /re | /resms | Zum Antworten auf die letzte SMS |
| /readv | - | Zum Antworten auf die letzte Werbung |
| /fan | - | Gibt ein Autogramm an den angegebenen Spieler |
| /pb | /paintball | Kurzbefehl für /paintball, zählt die Spieler im Paintball |
| /time | - | Rechnet die Krankenhaus- und Knastzeit in Minuten um und zeigt sie im Chat an |
| /anwalt | - | Zum Rufen eines Anwalts in die aktuelle Strafanstalt |
| /savestats | - | Zum Speichern der Statistiken mit /time |
| /ja | /jas, /jam | Ja, was kann ich für dich tun? |
| /kcall | - | Zum Anrufen eines Spielers anhand des Namens |
| /ksms | - | Zum Schreiben einer SMS an einen Spieler anhand des Namens |
| /p | - | Zum Annehmen eines Anrufes |
| /h | - | Zum Auflegen eines Anrufes |
| /ab | - | Anrufbeantworter |
| /tag | - | Guten Tag, wie kann ich dir helfen? |
| /bye | - | Ich wünsche dir noch einen schönen Tag. Auf Wiedersehen! |
| /fg | - | Kurzbefehl für /festgeld 1250000 |
| /ap | - | Kurzbefehl für /accept paket |
| /tanken | - | Zum automatischen Tanken an einer Tankstelle |
| /tankstellen | /tankstelle | Anzeigen der Tankstellen in einem Dialog sortiert nach Entfernung |
| /minuten | - | Rechnet Sekunden in Minuten um |
| /link | - | Speichert den letzten Link im Chat in der Zwischenablage |
| /savechat | - | Legt ein Backup des aktuellen Chatlogs an |
| /cc | /chatclear | Leert den Chat |
| /sani | - | Ruft einen Sanitäter |
| /addfriend | /addfreund | Zum Hinzufügen eines Freundes |
| /remfriend | /remfreund, /delfriend, /delfreund | Zum Löschen eines Freundes |
| /friends | /freunde | Zum Anzeigen der Freunde |
| /gegner | - | Zeigt alle Gegner an, die online sind |
| /\<fraktion\> | - | Zeigt alle Mitglieder der angegebenen Fraktion an |
| /gk | - | Zum Suchen eines bestimmten Gebäudekomplexes |
| /showgk | - | Zum Anzeigen eines bestimmten Gebäudekomplexes auf der Map mit einem Checkpoint |
| /showstores | - | Zeigt die freien Stores im Chat an |
| /checkpoint | - | Zum Setzen eines Checkpoints mit Koordinaten |
| /corrds | - | Zeigt die aktuellen Koordinaten an |
| /fpslock | - |  Zum Beschränken der FPS-Anzahl |
| /fpsunlock | - | Zum Aufheben der Beschränkung der FPS-Anzahl |
| /relog | - | Zum Reloggen (kann bei manchen Spielern zu einem Crash führen) |

### Job-System
Der Keybinder beinhaltet ein **vollständiges** Job-System, welches mit nur einer Taste bedient werden kann!
Der Job muss mit `/setjob` ausgewählt werden, danach muss man nicht mehr viel machen! Standardmäßig ist die Taste `J` zum Ausführen des Jobs eingestellt.
Für einige Jobs muss man noch weitere Informationen einstellen, damit alles rund läuft. `/setlinie` zum Einstellen der Busfahrer-Linie, `/wdskill` zum Einstellen des Waffendealer-Skills und `/dskill` zum Einstellen des Detektiv-Skills. Alles andere erkennt der Keybinder automatisch!
Außerdem werden alle durch das Jobben entstandenen Statistiken vom Keybinder gespeichert. Zum Beispiel kann man sie sich dann im Overlay anzeigen lassen!

## Download
- [Version mit Overlay](https://comniemeer.de/projects/8bitbinder/downloads/8Bit.zip)
- [Version ohne Overlay](https://comniemeer.de/projects/8bitbinder/downloads/8Bit_nov.zip)

## Whitelist
Der Binder besitzt eine Whitelist, wenn ihr ihn benutzen wollt, füllt folgendes Formular aus:
> Ingame-Name: <br>Fraktion: <br>Level:&nbsp;
**BITTE NUR HIER IM THREAD SCHREIBEN, NICHT PER PN**

Es besteht eine sehr geringe Chance, dass du nicht auf die Whitelist eingetragen wirst. Wenn dem der Fall sein sollte, weißt du sicherlich, warum.

## Credits
### Umsetzung
Programmierung: Martin<br>
Tester: -<br>
Namensvorschlag: Ferdi<br>
Layout Gist: cs_ (Chris)<br>

### Umgesetzte Vorschläge
- Funktionen des RobBinders in diesen Keybinder einfügen *von Killua_Bonobo*
- Gesamtgeld in den Stats anzeigen *von Peda_Furious*
- `/pd`, `/payday`, `[pdmoney]`, Warnung bei 5 L im Tank, Automatisch Kanister beim Tanken mitkaufen, /time verbessern *von Blade_Furious*
- Store-Robs und Geld zählen, Variablen für Overlay *von Don_Giovanni*
- Mitglieder der eigenen Fraktion im Gegner-Overlay ausblenden *von Chriz_Corey*
- Tankstellen in einem Dialog anzeigen *von Davide_Vercetti*
- Freunde-System einfügen *von Davide_Vercetti*