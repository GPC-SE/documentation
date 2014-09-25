**Table of Contents**
 - [Meldungen](#user-content-meldungen)
	- [Workflow](#user-content-workflow)
	- [Berechtigte Meldungen](#user-content-berechtigte-meldungen)
		- [Spam durch Bot](#user-content-spam-durch-bot)
		- [Spam durch User](#user-content-spam-durch-user)
		- [Flame](#user-content-flame)
		- [Off-Topic](#user-content-off-topic)
		- [Konsequenzen](#user-content-konsequenzen)
	- [Auswahl der Konsequenz](#user-content-auswahl-der-konsequenz)
	- [Sonderregelung zu Verwarnungen](#user-content-sonderregelung-zu-verwarnungen)
	- [Sonderregelung zu Bans / Sperren](#user-content-sonderregelung-zu-bans--sperren)
- [Falsch-Meldungen](#user-content-falsch-meldungen)

# TODO
* Reputationssystem konzeptionell integrieren
* (Dis)Like-Post-System konzeptionell integrieren

# Meldungen

Dieser Workflow beschreibt, wie mit Meldungen umgegangen wird.

Hier zunächst einige Erklärungen zum Löschen:

* Posts
  * Softes Löschen = Beitrag wird ausgeblendet und ein Kommentar für den Löschgrund hinzugefügt.
  * Hartes Löschen = Beitrag dauerhaft und endgültig löschen
* Threads
  * Softes Löschen = Thread wird ins Lösch-Forum verschoben
  * Hartes Löschen = Thread wird dauerhaft und endgültig gelöscht

## Workflow

1. Meldet ein User einen Beitrag, so wird dies in eine Moderations-Warteschlange eingereiht.
2. Berechtige Moderatoren werden darüber informiert (phpbb 3.1 notification?)
3. Der Moderator ...
     1. ... prüft ob es eine berechtigte Meldung ist
     2. ... bearbeitet die Meldung
     3. ... schließt die Meldung.

## Berechtigte Meldungen
Meldungen sind berechtigt, wenn der gemeldete Post / Thread einen dieser Inhalte besitzt:

1. Spam durch Bot
2. Spam durch User
3. Flame
4. Off-Topic

### Spam durch Bot

Bot-Spam ist Spam, der offensichtlich von einem Bot stammt und überhaupt nichts mit der GPC zu tun hat. Derartige Posts werden **hart gelöscht**.

### Spam durch User

Wenn ein User einen Beitrag verfasst, der in sich keinen konstruktiven Kommentar oder (angemessenes) Feedback beinhaltet, wird dieser **soft gelöscht**.

### Flame

Flames werden **soft gelöscht**, damit in extemen Fällen durch die Moderatoren und Admins der Verlauf eingesehen werden kann.

### Off-Topic

Vereinzelte Off-Topic posts sind okay. Driftet ein Thema wirklich ab, sollten die Off-Topic Beiträge entweder **soft-gelöscht** werden, wenn sie keinen Mehrwert generieren - oder in ein anderes Thema abgespalten werden. Ein Moderator entscheidet dabei, was im konkreten Fall sinnvoll ist.

### Konsequenzen
Fällt ein User häufiger auf, wird dies Konsequenzen haben. Diese sind in drei Eskalationsstufen aufgeteilt:

1. **Hinweis**: Bei Kleinigkeiten, wo evtl der Benutzer nichtmals weiß, dass er etwas falsch macht, wird diesem eine Nachricht geschrieben, mit der Aufforderung sein Verhalten anzupassen.
2. **Verwarnung**: Der Benutzer bekommt eine Verwarnung, wenn offensichtlich ein Verstoß gegen die Foren-Regeln vorliegt.
3. **Ban**: Der Benutzer wird gesperrt, wenn die Störung durch den Benutzer das Foren-Klima gefährdet.

## Auswahl der Konsequenz

Welche Konsequenz gezogen wird, wird zunächst durch den Moderator entschieden, der die Meldung bearbeitet. In extemen Fällen kann das ein sofortiger Ban sein.

Hinweise werden bei Kleinigkeiten, wo der User vielleicht nichtmals weiß, dass er etwas falsch macht, per PN an den User geschickt. Verwarnungen werden bei offensichtlichen Verstößen gegen die Foren-Regeln ausgesprochen (z. B. bei Flames). Sperren sollten genutzt werden, wenn weitere Vergehen durch einen User wahrscheinlich sind.

## Sonderregelung zu Verwarnungen
Erhält ein User innerhalb eines halben Jahres mehr als 3 Verwarnungen, ist die Empfehlung, dass das Team beim nächsten GPC-Meeting darüber spricht und ggf. weitere Konsequenzen überlegt.

## Sonderregelung zu Bans / Sperren

Jeder Ban ist zunächst temporär bis zum nächsten GPC-Meeting. Dort werden die Geschenisse besprochen und weiteres beschlossen. Dauerhafte Bans werden dadurch nicht nur durch eine Person willkürlich ausgesprochen, sondern im Team abgesegnet.

# Falsch-Meldungen

Manchmal ist nicht klar, ob ein Beitrag gemeldet werden sollte oder nicht. Bei unklaren Fällen, wird ein Moderator entscheiden und entweder die Meldung direkt schließen oder den normalen Meldungs-Workflow anwenden.

Bei offensichtlichen und/oder mehrfachen Falsch-Meldungen oder Spam durch Meldungen, wird eine Verwarnung ausgesprochen und die Meldung geschlossen. Im extrem Fall kann auch hier eine sofortige Sperre vor weiteren Falsch-Meldungen schützen.
