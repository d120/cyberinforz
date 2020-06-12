# IT-Infrastruktur

**An der Universität und am Fachbereich gibt es eine ganze Menge Technik, die auch großteils Studierenden zur Verfügung steht. Im Folgenden wird erklärt, was es so alles gibt und wer dafür zuständig ist.**

## Fachbereich

### ISP

Die [ISP (Infrastruktur und studentischer Poolservice)][1] bzw. früher Rechnerbetriebsgruppe (RBG) unterhält einen Großteil der IT-Infrastruktur im Robert-Piloty-Gebäude und bietet viele Dienstleistungen für Fachgebiete und Studierende. So betreibt die ISP unter anderem etwa 15 Server und mehr als 100 Pool-Rechner, die regelmäßig gewartet und aktualisiert werden.

### Account

Alle Studierenden der Informatik sowie anderer Studiengänge mit Informatikanteil (wie z.B. CE, iST, EtIt) können einen ISP/RBG-Account beantragen, um die Dienste der ISP zu nutzen. Der Account wird im [ISP-Support-Portal][2] beantragt und verwaltet. Der Benutzername entspricht dabei der TU-ID. Der Account bleibt jeweils ein Semester aktiv und muss dann wieder im [ISP-Support-Portal][2] verlängert werden. Rechtzeitig vor der Sperrung wird eine Benachrichtigung an die ISP/RBG-E-Mailadresse (s.u.) gesendet. Wenn ein Account zwei Semester lang gesperrt war, wird er gelöscht.

### ISP-Poolräume

Die ISP betreibt auf Ebene 0 zwei große PC-Poolräume. Im C-Trakt befindet sich der C-Pool, der mit etwa 100 PC-Arbeitsplätzen ausgestattet ist. Auf diesen Rechnern läuft standardmäßig die Linux-Distribution Linux Mint. Weiterhin gibt es noch einige Notebook-Arbeitsplätze. Der E-Pool im E-Trakt besitzt hauptsächlich Notebook-Arbeitsplätze und nur wenige PC-Arbeitsplätze.

Der C-Pool ist montags bis freitags von 7:30 Uhr bis 20 Uhr geöffnet. Der E-Pool ist neben diesen Öffnungszeiten auch nachts und an Wochenenden mit einem Transponder zugänglich.

In den Poolräumen stehen Laserdrucker zur Verfügung. Alle Studierenden erhalten pro Monat eine kostenlose Druckquota von 50 Seiten auf ihr Guthabenkonto von PaperCut. Der aktuelle Stand kann [hier][3] eingesehen werden. Unverbrauchtes Guthaben verfällt bis zu 100 Seiten nicht. Weiteres und farbiges Drucken ist nur beim HRZ möglich.
Durch PaperCut ist es möglich, sowohl über die Poolrechner als auch über den eigenen Rechner als auch über das [Webinterface][3] zu drucken.
Aufträge aus der eigenen Warteschlange gehen in Druck, sobald man seine Athenekarte auf das Kartenlesegerät des Druckers hält oder den Druck in der Weboberfläche freigibt.

Allen Studierenden steht auf den Poolrechnern jeweils 1 GB Speicherplatz zur Verfügung, für größere Datenmengen können nach [dieser Aussage][4] auch temporäre Ordner genutzt werden. Die Daten dort werden allerdings jede Nacht gelöscht.

Mittels [SSH][5] kann man sich von einem beliebigen Rechner aus auf den Poolrechnern einloggen, um die Daten und Programme zu nutzen. Dazu muss man vorher einen SSH-Schlüssel auf den Poolrechnern hinterlegen. Eine Anleitung dazu ist ebenfalls [hier][5] zu finden.
Wer es lieber grafisch mag, kann auf der SSH-Verbindung aufbauend auch eine VNC-Verbindung starten. Wie das geht, steht [hier][6].

## Uniweit

### HRZ

Das [Hochschulrechenzentrum (HRZ)][10] bietet ähnlich wie die ISP IT-Dienste für die ganze Universität an. Es bietet jedoch noch einiges mehr als die ISP.

### Account

Ein HRZ-Account besteht aus der TU-ID und dem dazugehörigen Passwort. Er wird mit dem auf der Immatrikulationsbescheinigung aufgedruckten Passwort aktiviert und bietet Zugang zu den meisten IT-Systemen an der TU Darmstadt. Mit diesem Account ist auch ein E-Mail-Postfach verknüpft, das direkt abgefragt oder weitergeleitet werden kann. Eine Anleitung dazu gibt es [hier][11].

### Services des HRZ

Eine der wichtigsten Aufgaben des HRZ ist die flächendeckende Versorgung des Campus mit WLAN. Seit 01. Oktober existiert nur noch ein WLAN-Netzwerk: das verschlüsselte eduroam. Eduroam ist an vielen europäischen Universitäten verfügbar und kann mit dem Zugang der TU Darmstadt auch dort genutzt werden. Zur Anmeldung werden die [TU-ID und das zugehörige Passwort][12] benötigt. Um von außerhalb des Campus auf das Uninetz zuzugreifen, etwa um E-Books aus der Bibliothek zu lesen oder interne Webseiten zu betrachten, muss man sich mittels VPN verbinden. Anleitungen dazu sind ebenfalls [hier][12] zu finden.

Weiterhin stellt das HRZ die [Athenekarte][13] bereit. Sie bietet momentan die Möglichkeit, bargeldlos in den Mensen und Bistros des Studierendenwerks zu bezahlen und dient als Leseausweis für die Universitäts- und Landesbibliothek. An den Pooldruckern können damit Druckaufträge bezahlt werden und auch der Filmkreis setzt sie als bargeldloses Zahlungsmittel im Unikino ein.

Das HRZ bietet ebenso wie die ISP Rechnerpools an, die allerdings mit Windowsrechnern ausgestattet sind. Zugang erhält man mittels TU-ID und Passwort. In den Poolräumen stehen diverse Drucker, die für wenig Geld in verschiedenen Größen, Papiersorten und Farben drucken können.

Zur Unterstützung der Lehre bietet das HRZ auch mehrere [E-Learning-Angebote][14], wie z.B. OpenLearnWare, das eine steigende Anzahl von Vorlesungsaufzeichnungen bereithält.

Im [Service-Center des HRZ][15] erhält man Hilfe bei Problemen mit WLAN, VPN und den weiteren Diensten. Außerdem ist es dort möglich, Hardware wie Beamer, Leinwände und Videokameras auszuleihen.

*Tobias Otterbein, überarbeitet von Dorothea Treitz und Tim Pollandt*

[1]: https://www.isp.informatik.tu-darmstadt.de
[2]: https://support.rbg.informatik.tu-darmstadt.de
[3]: https://print.informatik.tu-darmstadt.de/user
[4]: https://support.rbg.informatik.tu-darmstadt.de/blog/2014/03/temp-speicherplatz-fuer-24h
[5]: https://support.rbg.informatik.tu-darmstadt.de/wiki/de/doku/computerhilfe/ssh
[6]: https://support.rbg.informatik.tu-darmstadt.de/wiki/de/doku/computerhilfe/vnc
[7]: https://support.rbg.informatik.tu-darmstadt.de/wiki/de/doku/computerhilfe/mail/email
[8]: https://webmail.rbg.informatik.tu-darmstadt.de/mail
[9]: https://support.rbg.informatik.tu-darmstadt.de/wiki/de/doku/account/transponder
[10]: https://www.hrz.tu-darmstadt.de
[11]: https://www.hrz.tu-darmstadt.de/mail/e_mail/mail_studierende
[12]: https://www.hrz.tu-darmstadt.de/netz/netzzugang_internet
[13]: https://www.hrz.tu-darmstadt.de/angebote_studierende/studierende_athenekarte
[14]: https://www.e-learning.tu-darmstadt.de/elearning
[15]: https://www.hrz.tu-darmstadt.de/support/hrz_service
