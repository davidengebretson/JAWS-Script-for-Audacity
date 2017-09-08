﻿13.4.2017 JAWS skript für Audacity V2.0 (für Skript Version 2.1.0) von Gary Campbell <campg2003@gmail.com> und Dang Manh Cuong <dangmanhcuong@gmail.com>

Dieses Jaws Skript Paket bietet Unterstützung für Audacity 2.0.0 und neuer.

# Features:
- Tastenkombinationen zur Ansage der Selektion Start, Selektion Ende oder Dauer, und der Audio Position, von überall im Hauptfenster.
- Tastenkombinationen um den Fokus zu den  Selektion Start und Selektion Ende / -Dauer Steuerelementen zu bewegen.
- Anzeigen der Hilfe für die Jaws und Audacity Tastenkombinationen.
- Der Audacity Leitfaden für Jaws Anwender von David Bailes ist direkt aus der Audacity Tastenkombinationen Hilfe erreichbar (Jaws Taste + W).
- Ansage der wichtigsten Fensterbereiche: Werkzeugleisten, Spuren Panel und Selektion Leiste, wenn der Fokus zwischen diesen gewechselt wird.
- Spricht den Namen der Werkzeugleiste, wenn der Fokus von einer Werkzeugleiste zu einer anderen verschoben wird.
- Wenn der Fokus in einer Werkzeugleiste ist, kann mit CTRL + Tab zur nächsten und mit CTRL + Shift + Tab zur vorherigen Werkzeugleiste gewechselt werden.
- Jaws Taste + Entfernen spricht den aktuellen Transportstatus: Stop, Wiedergabe, Wiedergabe-Pause, Aufnahme oder Aufnahme-Pause.
- Spricht die Cursor Position wenn die Pfeil nach links oder Pfeil nach rechts Tasten gedrückt werden, Audacity gestoppt ist und der Fokus im Spuren Panel ist.
- Beim Erweitern oder Reduzieren der Selektion mit Tastenkombinationen wird die neue Position oder Dauer angesagt.
- Informiert, wenn keine Spuren in einem Projekt vorhanden sind und deshalb die gewählte Operation nicht angewendet werden kann.
- Tastenkombinationen, um die Werte des Wiedergabe- und Aufnahmepegels anzusagen (maximale Spitze).
- Die Steuerung der Lautstärke und des Panoramas der Spur werden nun an die Applikation durchgereicht, wenn der PC Cursor aktiviert und der Fokus im Hauptfenster ist. Andernfalls werden die Standard Funktionen zur Maussteuerung ausgeführt.
- In vielen VST-Plugins kann das Preset Steuerelement mittels Tastenkombination fokussiert und Presets geladen und gespeichert werden.
- In vielen Plugin Dialogen werden Namen und Werte der Steuerelemente angesagt.
- Unterstützung mehrere Sprachen: Englisch, Spanisch und Deutsch werden unterstützt. Ebenso ist eine Übersetzung der readme Datei in Vietnamesisch vorhanden. Vielen Dank an Nguyen Hoang Giang, Dang Manh Cuong and Le Thi Theu dies anzubieten. Diese Datei audacity_readme_vi.txt ist im Installationsverzeichnis im Programme Ordner zu finden.
- Spuren können durch angabe einer Nummer aktiviert oder an eine bestimmte Position verschoben werden. Ebenso kann eine bestimmte Spur "gemerkt" werden, um später diese Spur zu aktivieren oder eine andere Spur an diese gemerkte Position zu verschieben.
- Feedback, wenn eine Spur mit der Tastatur verschoben wird (siehe weiter unten)
- Der Installer kann nun die Skripts für alle Benutzer oder für den aktuellen Benutzer installieren. Werden die Skripts für alle Benutzer installiert, werden diese in das gemeinsame Scripts Verzeichnis kopiert, auch für Jaws 17. 
- Während der Wiedergabe / Aufnahme bewirkt die Enter Taste das Pausieren und Fortsetzen. CTRL + Enter sendet in diesem Fall Enter. Ich mag dies, da die Num Pad Enter Taste einfacher gefunden werden kann als die P Taste, wenn die Hände nicht auf der Tastatur liegen. Diese Funktion kann mit einer Option im Schnelleinstellungs Dialog von Jaws deaktiviert werden. Probiere es aus und lass uns wissen, ob das für Dich funktioniert und ob Du dies magst.
 
# Installieren und Deinstallieren der Skripts

## Installieren:

1. Platziere den Installer in einem Ordner auf Deinem Computer.
2. Starte den Installer um die Dateien zu installieren.

Drei Installationstypen werden unterstützt:

- Nur Skripts:Installiert nur die Skripts. Es wird keine Option zur Deinstallation und kein Verzeichnis im Ordner Programme erstellt.
- Vollständig: Installiert die Skripts im Ordner Scripts für die gewählte Jaws Version und Sprache. Erstellt einen Ordner  in %programfiles%, (%localappdata% für aktuellen Benutzer Installation). In den Installationsordner werden die Deinstallationsoption und optionale zusätzliche Dateien wie die readme Datei kopiert.
- Benutzerdefiniert: Wie vollständig, erlaubt jedoch die Installation der Quelldaten des Installers.

Für die vollständige und die benutzerdefinierte Installation für alle Benutzer werden die Deinstallationsoption und die Readme Datei im Installationsverzeichnis installiert.

Wenn der nur Skripts Typ gewählt wird, werden die readme und die whats new Dateien in den Jaws Scripts Ordner jeder Version installiert, und whatsnew.md wird in audacity_whatsnew.md umbenannt. (die readme Datei in Vietnamesisch wird bei einer nur Skripts Installation nicht kopiert)

Wenn die Berechtigungen des Benutzers die Installation für alle Benutzer erlaubt, wird eine Installation für alle Benutzer ausgeführt, andernfalls wird die Installation für den aktuellen Benutzer ausgeführt. Wenn die Berechtigungen die Installation für alle Benutzer erlaubt, kann mit dem Kommandozeilenparameter /currentuser die Installation für den aktuellen Benutzer erzwungen werden.

Bei der alle Benutzer Installation, auf der Seite Versionen/Sprache, kann zwischen der Installation für alle Benutzer oder der Installation für den aktuellen Benutzer gewählt werden.

Der Installer erlaubt es auszuwählen, in welche Jaws Version und Sprache die Skripts installiert werden. Er kompilliert das Skript Paket für jede Version. Beachte, dass das Skript Paket nur für die Sprache der aktuell laufenden Jaws Version sauber kompilliert werden kann.

Wenn Du den Installer modifizieren möchtest, oder Du betrachten möchtest, wie er funktioniert, kannst Du die Quelldaten des Installers installieren, in dem im benutzerdefinierten Installationstyp die Option Installer Source installieren gewählt wird.

## Deinstallieren:
Das Paket kann unter Programme und Features deinstalliert werden (Programme hinzufügen oder entfernen). Alternativ kann die Datei uninst.exe im Installationsverzeichnis ausgeführt werden (%programfiles(x86)%\Jaws Script for Audacity oder %localappdata%\Jaws Script for Audacity).

Wenn der Uninstaller erkennt, dass die Skripts seit der Installation modifiziert wurden, muss das Löschen der Skripts bestätigt werden. Wird ja gewählt, werden alle modifizierten Dateien gelöscht, wird nein gewählt, bleiben alle Skripts unverändert. Die Konfigurationsdatei (audacity.jcf oder audacity.jsi) wird nicht entfernt.

# Verwenden der Skripts
Hinweis: Das Skript spricht Namen einiger Audacity Tastenkombinationen und verwendet andere um bestimmte Operationen auszuführen. Wenn in Audacity im Menü Einstellungen, Tastatur diese Tastenkombinationen geändert werden, müssen auch dessen Zuordnungen in der Datei audacity.jkf geändert werden, damit das Skript weiterhin sauber funktioniert.

## Grundlagen
Nach der Installation spricht das Skript eine Willkommen Meldung, wenn Audacity erstmals den Fokus erhält. Du kannst eine Liste der vom Skript bereitgestellten Tastenkombinationen anschauen, in dem Du Jaws Taste + H drückst ( Hotkey Hilfe). Eine Liste mit Audacity Tastenkombinationen erhälst Du mit Jaws Taste + W. Diese Seite enthält auch einen Link, mit dem der Audacity Leitfaden für Jaws Anwender von David Bailes im Browser geöffnet werden kann. 

Du kannst die Selektion Start und Selektion Ende Position oder die Selektion Dauer ansagen mit Alt + [ und Alt + ]. Zwei Mal kurz nacheinander gedrückt wird das jeweilige Eingabefeld zur Eingabe der Position fokussiert. Beachte, dass Alt + ] "Ende" oder "Länge" spricht, je nach gewähltem Optionsfeld. Bei aktiviertem PC Cursor wird mit Alt + Entfernen die Audio Cursor Position angesagt (das ist Hilfreich während der Wiedergabe oder Aufnahme). Zwei Mal kurz nacheinander gedrückt wird die normale Jaws Funktion ausgeführt. Mit Jaws Taste + Entfernen wird der aktuelle Transport Status von Audacity angesagt: gestoppt, Wiedergabe, Wiedergabe Pause, Aufnahme oder Aufnahme Pause (In früheren Versionen von Audacity ist dieser Status in der Statuszeile erreichbar).

Die Skript Version wird mit Jaws Taste + Ctrl + V angesagt und durch zwei Mal kurz im virtuellen Betrachter angezeigt, eben so in der Hotkey Hilfe.

Die URL für den Zugriff zum Audacity Guide für Jaws Anwender kann mit Ctrl + Shift + J geändert werden. Dies öffnet einen Dialog mit einem Textfeld, welches die URL enthält. Editiere oder ersetze diese und wähle ok.

Bei der Eingabe der Bezeichnung einer Textmarke spricht Jaws aus Gewohnheit die Funktionsnamen von Audacity der zugeordneten Buchstabentasten, sobald diese Buchstaben in der Textmarkenbezeichnung eingetippt werden. Wir unterdrücken nun dieses Verhalten wenn die standard Methoden zum Erstellen von Textmarken verwendet werden. Dieses Feature wird mit  Ctrl + B und Ctrl + M aktiviert und durch Drücken von Enter wieder deaktiviert (dies wird auch deaktiviert durch aktivieren einer anderen Spur oder durch Verlassen des Spuren Panel). Durch aktivieren einer Textmarkenspur und lostippen wird dieses Feature nicht aktiviert. Wenn die Standard Tastenkombinationen dieser Funktionen in Audacity geändert werden, müssen diese auch in audacity.jkf entsprechend angepasst werden.

Wenn der Fokus in einer Textmarkenspur ist, wird durch Drücken der Tabulator Taste versucht, die "aktuelle" Textmarke zu sprechen. Dies wird getan, in dem Text mit weissem Hintergrund gesucht wird. Das funktioniert nicht immer, besonders bei vielen vorhandenen Textmarken. 

## Skript Optionen

Das Skript hat verschiedene Optionen, mit denen dessen Features konfiguriert werden können. Diese können mit JAws Taste + V erreicht werden. Für Jaws Versionen vor 13  sind diese im Ordner personal settings der Jaws Installation in der Datei audacity.jsi definiert. Für Version 13 und neuer sind diese in der Datei audacity.jcf, im Abschnitt NonJCFOptions hinterlegt. Beim Aktualisieren einer Version vor 13 auf die Version 13 oder neuer werden diese Einstellungen nicht aus audacity.jsi übernommen. In diesem Fall müssen die Einstellungen erneut vorgenommen werden.

## Spuren aktivieren und verschieben

Es ist möglich eine Spur durch eingabe einer Zahl zu aktivieren, eine Spur durch eingabe einer Zahl an eine bestimmte Position zu verschieben, und eine bestimmte Spur zu "merken", um diese Spur zu einem späteren Zeitpunkt wieder zu aktivieren, oder die aktive Spur an die gemerkte Position zu verschieben. Auch beim Verschieben einer Spur mit der Tastatur wird hilfreiches Feedback gesprochen. Dieses Feature funktioniert mit Audacity ab Version 2.1.1 und erfordert ein paar Anpassungen der Audacity Konfiguration. Die Audacity Funktion Fokussierte Spur nach oben verschieben muss Ctrl + Shift + Pfeil nach oben und die Funktion Fokussierte Spur nach unten verschieben Ctrl + Shift + Pfeil nach unten zugeordnet werden. Gehe wie folgt vor:

1. Öffne den Einstellungen Dialog (Ctrl + P) und wähle die Kategorie Tastatur (Taste K).
2. Tabbe zum Eingabefeld und gebe "Fokussierte Spur" ein (ich verwende die Baum Ansicht).
3. Tabbe zur Baumansicht und wähle die Funktion Fokussierte Spur nach unten verschieben
4. Tabbe zum Tastatur-Bindungen Eingabefeld und drücke Ctrl + Shift + Pfeil nach unten
5. Tabbe zum Setzen Schalter und drücke die Leertaste, um die Tastenkombination zuzuordnen.
6. Drücke zwei Mal Shift + Tab, um in die Baumansicht zurück zu gelangen.
7. Wähle die Funktion Fokussierte Spur nach oben verschieben und ordne die Tastenkombination Ctrl + Shift + Pfeil nach oben auf die gleiche Weise wie zuvor zu.
8. Tabbe zu ok und drücke die Leertaste.

Wenn andere Tastenkombinationen zugeordnet werden, muss die Datei audacity.jkm entsprechend angepasst werden.

Einmal konfiguriert, kann mit Jaws Taste + A, G eine bestimmte Spur aktiviert werden. Das Skript fragt nach einer Zahl, durch eingeben der Zahl der gewünschten Position in der Spurliste wird die entsprechende Spur aktiviert. Durch voranstellen eines +  um die entsprechende Zahl nach unten (zu höheren Spurnummern), durch Voranstellen eines - nach oben. Mit Jaws Taste + A, M wird die aktive Spur an eine bestimmte Position verschoben. Die aktive Spur kann mit Jaws Taste + A, K "gemerkt" werden. Danach kann mit Jaws Taste + A, Shift + G jederzeit die gemerkte Spur aktiviert werden oder mit Jaws Taste + A, Shift + M die aktive Spur an die gemerkte Position verschoben werden. Beachte, dass dieses "Merken" lediglich die Position der Spur in der Spurliste "notiert". Wenn davor Spuren eingefügt oder verschoben werden, zeigt der Vermerk auf die falsche Spur.

Sprich Zeile (Jaws Taste + Num Pad 5) sagt die aktuelle Spurnummer und die Anzahl  aller Spuren an, wenn der Fokus im Spuren Panel ist. (Einige mögen denken "Aber Audacity sagt bereits Spurnummern". Das stimmt wenn eine Spur erstellt wird, jedoch nicht, wenn sie umbenannt wird. Oder wenn es das Resultat vom Importieren einer Datei ist.)

# Bekannte Probleme

1. Diese Version des Skripts bietet die Möglichkeit des Deaktivierens der Sprachmeldungen (Stille) während der Vorschau von Effekten (Vorhören vor der Anwendung einer Operation auf die Audiodaten). Manchmal wird diese Stille nicht richtig nach der Vorschau wieder ausgeschaltet. Dies kann durch kurzes Wechseln des Fokus weg von Audacity und wieder zurück behoben werden.

2. Die Position Steuerelemente liefern manchmal ungekürzte Zeitwerte. Das geschieht, da die JAWS GetWindowText Funktion lediglich Werte ohne h, m, s etc. liefert. Wir wissen nicht, wodurch dies ausgelöst wird. Ich konnte dies durch Beenden und neu Starten von Audacity korrigieren. Das Phänomen wurde in Jaws 10, 15, 16 und 17 beobachtet. Ich habe beobachtet, dass dieses Problem manchmal von alleine verschwindet. 

3. Wenn das "Enter pausiert während Wiedergabe / Aufnahme" Feature aktiviert ist (das ist die Voreinstellung), führt Enter nicht zum Selektieren und Deselektieren der aktiven Spur während der Wiedergabe oder Aufnahme. Verwenden Sie in diesem Fall Ctrl + Enter anstatt Enter. 

4. Wenn die Num Pad Enter Taste redefiniert und die erweiterten Tasten zur unterschiedlichen Belegung konfiguriert sind, werden denoch beide Enter Tasten identisch zugeordnet. Wenn dieses Feature nicht erwünscht ist, kann es deaktiviert werden, in dem in audacity.jkm ein Semikolon vor die Zeilen Enter, Numpad Enter und Ctrl + Enter eingefügt wird und in audacity.jss die Semikolons in den Zeilen, die /* und */ vor und nach den Skripts Enter und CtrlEnter enthalten. Wenn audacity.jss modifiziert wird, ändern Sie in der Version Konstanten das Datum. So wissen Sie das genau, wenn Sie mit uns darüber kommunizieren. 

5. Der Jaws Skript Compiler kompilliert nur für die aktuell laufende  Sprachversion von Jaws (siehe weiter unten).

6. In Jaws Versionen vor 13 erscheint die Tastenkombination Jaws Taste + V für die Skriptspezifischen  Optionen nicht in der Hotkey Hilfe. Die Tastenkombination funktioniert trotzdem. Wie auch immer, wir können dies beheben, wenn  sich zeigt, dass dies ein Problem sein sollte.


# Unterstützung mehrerer Sprachen
Diese Version des Installer Frameworks enthält den ersten Wurf, welche die Installation der Skripts in mehreren Sprachen unterstützt. Es behandelt nun Version / Sprache Paare wie bisher Versionen behandelt wurden. So  werden nun in der Version Auswahlliste Einträge wie 16.0 / enu angezeigt. Aktuell werden Englisch, Spanisch und Deutsch unterstützt. Fernando Gregoire hat die spanische Übersetzung bereitgestellt. Gracias! Michael Vogt hat die deutsche Übersetzung bereitgestellt. Dankeschön!

Obschon der Installer die Skriptdateien in die Ordner der gewählten Sprache installiert und kompilliert, kompilliert der Jaws Script Compiler die Scripts nur in der Sprache der aktuell laufenden Jaws Version. Deshalb muss nach der Installation Jaws in den entsprechenden Sprachen gestartet und die Skripts kompilliert werden.

# Hinweise für Skript Entwickler
Wenn Sie die Skriptdateien modifizieren, aktualisieren Sie bitte die Version Konstante in der Nähe des Anfangs der Datei audacity.jss. Das ist besonders dann wichtig, wenn Sie das Skript Paket weitergeben. Auch wenn Sie die  modifizierten Skript Dateien ausschliesslich selbst verwenden, stellt das Vorgehen sicher, dass wir wissen, dass es sich um eine modifizierte Version handelt, wenn Sie damit mit uns in Kontakt treten.

Meldungen und String Konstanten für das Jaws Skript sind in den Dateien audacity.jsm und audacity.qsm.

Die Meldungstexte des Installers sind nun lokalisierbar. Die Meldungstexte wurden nun vom Programmcode getrennt, so dass für jede Sprache separate Message Sets präpariert werden können. Aktuell werden Englisch, Spanisch und Deutsch unterstützt. Meldungstexte sind in .nsh Header Dateien mit Dateinamen wie *_enu.nsh oder *_lang_enu.nsh deklariert.

Dieses Paket wird jetzt auf GitHub gehostet. Das Repository ist unter <https://github.com/campg2j003/JAWS-Script-for-Audacity>. Wenn Sie Änderungen an den Skripts veröffentlichen möchten, llesen Sie bitte [CONTRIBUTING.md](CONTRIBUTING.md) im repository.

# Hinweise für Übersetzer
Beachte dass readme.html aus readme.md generiert wird, welche nur im GitHub Repository zu finden ist. Siehe [CONTRIBUTING.md](CONTRIBUTING.md) für weitere Informationen.

Note that the script is compiled using #pragma usePoFile 0.
Beachte, dass das Skript mit #pragma usePoFile 0 kompiliert wird.
 

# Abschliessende Anmerkungen
Das Skript wurde Entwickelt mit Audacity 2.0.3, 2.0.4, 2.0.5, 2.1.0, 2.1.1 und 2.1.2.  Es wurde auch getestet mit 2.1.3 alpha versionen.  Es wird wahrscheinlich mit allen Jaws Versionen ab 5.0 funktionieren, obschon die Optionen für Audacity in den Jaws Schnelleinstellungen nicht sehr gut aussehen, was nicht getestet wurde (ich erinnere daran, dass eine Jaws Funktion die wir verwenden, auf FSDN mit "erfordert Jaws 10 oder neuer" vermerkt ist. Die letzten Programmierarbeiten wurden mit Jaws 17 und 18 auf einem 64 Bit Notebook mit Windows 10 ausgeführt. Auch wenn Support für frühere Versionen von Jaws angeboten wird, wurde  der aktuelle Code nicht mit diesen getestet. Zum jetzigen Zeitpunkt bieten wir keinen spezifischen Support für Braille an.

Ich bin  interessiert an Feedback zu dem Skript und Vorschlägen zu Verbesserungen, kann jedoch keine Updates versprechen.

# Hier ist der Text der Jaws Hotkey Hilfe


Ansagen der Start Position der Selektion: Alt+ü
Ansagen der Ende Position oder der Länge der Selektion: Alt+Plus Taste (Umlaut Taste)
Fokus zum Eingabefeld der Start oder Ende Position der Selektion platzieren: zwei Mal kurz aufeinander drücken.
Ansagen der Position des Audio Cursors: Alt+Entfernen
Bei aktiviertem PC-Cursor: zwei Mal kurz nacheinander drücken.

Erhöhen der Lautstärke der aktiven Spur: Alt+Umschalt+Pfeil Rauf
Verringern der Lautstärke der aktiven Spur: Alt+Umschalt+Pfeil Runter
Panorama der aktiven Spur nach links Alt+Umschalt+Pfeil Links
Panorama der aktiven Spur nach rechts: Alt+Umschalt+Pfeil Rechts.
Die letzten vier Tastenkombinationen ersetzen die Standard Jaws Skripts der Steuerung des Mauszeigers, wenn der Fokus im Hauptfenster ist. Durch Aktivieren
des Jaws Cursors kann die originale Jaws Maussteuerung im Hauptfenster verwendet werden.

Ansagen des Aufnahmepegels: g
Fokus zum Eingabefeld des Aufnahmepegels: zwei Mal kurz nacheinander drücken
Ansagen des Wiedergabepegels: h
Fokus zum Eingabefeld des Wiedergabepegels: zwei Mal kurz nacheinander drücken.

Eine bestimmte Spur aktivieren durch angeben einer Zahl: Einfügen+a, a
Die Aktive Spur an eine bestimmte Position verschieben, durch angeben einer Zahl: JAWS Taste+a, m
Die aktive Spur merken: JAWS Taste+a, k
Die zuletzt gemerkte Spur aktivieren: JAWS Taste+a, Umschalt+g
Die zuletzt gemerkte Spur aktivieren und die zuvor aktive Spur merken: JAWS Taste+a, x
Aktive Spur an die zuletzt gemerkte Position verschieben und diese merken: Einfügen+a, Umschalt+m

Meldungen der Sprachausgabe ein- und ausschalten (muten des Synthesizers): Umschalt+Einfügen+S
Ansagen bestimmter Audacity Prozesse aktivieren / deaktivieren: Steuerung+` (Paragraph Taste)
Hinweis: dies verdoppelt die Ansagen von Audacity Nachrichten in den Jaws Schnelleinstellungen Optionen. Weitere Informationen in what's new.md.

Zur nächsten Werkzeugleiste navigieren, wenn der Fokus in einer Werkzeugleiste ist: Steuerung+Tab
Zur vorherigen Werkzeugleiste navigieren, wenn der Fokus in einer Werkzeugleiste ist: Steuerung+Umschalt+Tab

Transport Status ansagen (Wiedergabe, Aufnahme, Pause, Stop): JAWS Taste+Entfernen
Alle Optionen der Jaws Skripts für Audacity auf die Standardwerte zurücksetzen: Umschalt+Steuerung+` (Paragraph Taste)
Wechseln zwischen den beiden Listen im Ketten editieren Dialog: F6

Audacity Tastenkombinationen Hilfe: Einfügen+w
Standard Windows Tastenkombinationen Hilfe: Einfügen+w zwei Mal kurz nacheinander

Pause während Wiedergabe / Aufnahme an / aus: wenn die "Eingabetaste unterbricht Wiedergabe / Aufnahme" Option aktiviert ist, bewirkt das Drücken der Eingabe
Taste das Senden der Pause Taste. In dieser Konstelation bewirkt Steuerung+Eingabe das Senden der Enter Taste.

In einigen VST-Plugins, wie beispielsweise dem L1V:
Fokus auf die "Preset" Schaltfläche: Alt+P
Um ein existierendes Preset zu laden: Alt+C
Speichern der aktuellen Einstellungen des VST-Plugins als Preset: Alt+G

Wenn die "Stille Vorschau" aktiviert ist und in einem Effekt Dialog die Vorschau Taste gedrückt wird, wird manchmal die "Stille Vorschau" nicht erwartungsgemäss
deaktiviert. Dies führt zu fehlenden Jaws Ansagen beim Wechsel des Fokus. Das kurzzeitige Wechseln zu einer anderen Anwendung behebt das Problem.

Ändern der Einstellungen der Audacity Skripts:   Einfügen+V.

Um die URL des Jaws Guide für Audacity zu ändern: Umschalt+Steuerung+J
 

Viel Spass!