---
layout: leftnav
title: Häufig gestellte Fragen und Probleme
menu: subnav
category: Verwalten von Kennwörtern
---

Im Anschluss finden Sie eine Liste von Fragen und Problemen, auf die Sie möglicherweise beim Arbeiten mit Single Sign-On stoßen.

## Ich wurde in einer Fehlermeldung über den baldigen Ablauf des Kennworts benachrichtigt

Informationen werden am besten gesichert, wenn Sie das Kennwort regelmäßig ändern. Abhängig von der Konfiguration im Unternehmen erinnert Sie Single Sign-On, wenn die Kennwörter zu lange verwendet wurden.

Sie erhalten diese Meldungen, bis Sie das Kennwort ändern.

## Ich möchte Single Sign-On vorübergehend anhalten

Manchmal möchten Sie Single Sign-On ggf. nicht ausführen. Sie müssen z. B. an einer Anmeldeseite arbeiten, ohne dass Sie von Single Sign-On am Programm angemeldet werden.

Verwenden Sie in diesen Situationen das Feature "Anhalten" von Single Sign-On. Mit "Anhalten" beenden Sie die automatische Anmeldung, Single Sign-On bleibt jedoch geöffnet und kann von Ihnen verwendet werden.

## Das Programm hat mein neues Kennwort abgelehnt

Sie haben das Kennwort für ein bestimmtes Programm mit dem Assistenten für Kennwortänderungen geändert, wenn Sie sich jedoch am Programm anmelden, wird das neue Kennwort vom Programm als ungültig abgelehnt.

Wahrscheinlich wurde das neue Kennwort in Single Sign-On gespeichert, jedoch nicht vom Programm akzeptiert. Daher sendet Single Sign-On ein falsches Kennwort.

Beheben Sie das Problem mit dem Feature "Altes Kennwort wiederherstellen", wenn dieses Feature im Unternehmen den Benutzern zur Verfügung gestellt wird.

**Hinweis:** Sollte dieses Feature nicht verfügbar sein, wenden Sie sich an den Helpdesk.

## Wiederherstellen des alten Kennworts für ein Programm

1. Klicken Sie im Microsoft Windows-Infobereich (normalerweise ganz rechts auf der Taskleiste) mit der rechten Maustaste auf das Citrix Receiver-Symbol und klicken Sie dann auf **Kennwörter** > **Kennwörter verwalten**.
1. Wählen Sie im Fenster "Kennwörter verwalten" das gewünschte Programm oder die Website aus und klicken Sie auf **Bearbeiten**. Ein Dialogfeld mit den Eigenschaften des ausgewählten Programms wird angezeigt.
**Hinweis**: Möglicherweise hat das Unternehmen an dieser Stelle eine Identitätsüberprüfung festgelegt. Geben Sie in diesem Fall Ihren Windows-Benutzernamen und das Kennwort ein, wenn Sie dazu aufgefordert werden. (Wenn Sie sich mit einer Smartcard oder anderen Authentifizierungsmethode anmelden, für die kein Benutzername und Kennwort benötigt wird, prüfen Sie hiermit Ihre Identität, wenn Sie dazu aufgefordert werden.)
1. Klicken Sie auf **Altes Kennwort wiederherstellen** und bestätigen Sie die Aktion durch Klicken auf **Ja**.

## Ich habe keinen Zugriff auf meine Benutzerdaten

Bei der Anmeldung am Computer stellt Single Sign-On eine Verbindung mit dem Server her, auf dem das Unternehmen die Single Sign-On-Benutzerinformationen speichert. Wenn die Verbindung erfolgreich hergestellt und Ihre Identität bestätigt wird, startet Single Sign-On.

Wenn das Herstellen der Verbindung oder das Prüfen der Identität nicht erfolgreich ist, wird Single Sign-On nicht gestartet und Sie erhalten eine Fehlermeldung, dass der Zugriff auf die Benutzerdaten nicht möglich war. Wenden Sie sich in diesen Situationen an den Helpdesk.

## Mein Webbrowser funktioniert nicht mit Single Sign-On

Single Sign-On unterstützt nur die Verwendung von Microsoft Internet Explorer. Wenn Sie andere Webbrowser verwenden, erhalten Sie möglicherweise nicht die gewünschten Ergebnisse.

## Nach dem Abmelden meldet Single Sign-On mich erneut an

Wenn Sie sich manchmal von einem kennwortgeschützten Programm oder einer Website abmelden, geht das Programm auf das Anmeldedialogfeld zurück. Abhängig von der Single Sign-On-Konfiguration im Unternehmen reagiert das Programm auf die Anmeldeseite und meldet Sie wieder am Programm an.

Sie umgehen das Problem wie folgt:

* Verwenden Sie das Feature "Anhalten" von Single Sign-On (falls im Unternehmen verfügbar), bevor Sie sich abmelden.
* Wenn "Anhalten" nicht verfügbar ist, melden Sie sich vom Programm ab und schließen Sie schnell das Programmfenster, bevor Single Sign-On Sie erneut anmelden kann.

**Hinweis:** Wenden Sie sich an den Helpdesk und erklären Sie das Problem. Schlagen Sie vor, dass der Single Sign-On-Administrator in den erweiterten Einstellungen der Anwendungsdefinition **Nur die erste Anmeldung für diese Anwendung verarbeiten** aktiviert.

## Welche vorbereitenden Aufgaben muss ich für die Offlinearbeit ausführen?

Wenn Single Sign-On auf dem Computer installiert ist und nicht auf einem Server im Unternehmensnetzwerk ausgeführt wird, sollten Sie die Lizenz aktualisieren, bevor Sie offline arbeiten. Dies stellt sicher, dass Sie den ganzen Zeitraum für die Lizenzgültigkeit zur Verfügung haben, bevor Sie wieder eine Verbindung mit dem Unternehmensnetzwerk herstellen.

## Aktualisieren der Single Sign-On-Lizenz

1. Klicken Sie im Microsoft Windows-Infobereich (normalerweise ganz rechts auf der Taskleiste) mit der rechten Maustaste auf das Citrix Receiver-Symbol und klicken Sie dann auf **Kennwörter** > **Kennwörter verwalten**.
**Hinweis**: Möglicherweise hat das Unternehmen an dieser Stelle eine Identitätsüberprüfung festgelegt. Geben Sie in diesem Fall Ihren Windows-Benutzernamen und das Kennwort ein, wenn Sie dazu aufgefordert werden. (Wenn Sie sich mit einer Smartcard oder anderen Authentifizierungsmethode anmelden, für die kein Benutzername und Kennwort benötigt wird, prüfen Sie hiermit Ihre Identität, wenn Sie dazu aufgefordert werden.)
1. Klicken Sie auf "Info". Das Dialogfeld "Info über Citrix Single Sign-On" wird angezeigt.
1. Klicken Sie auf **Lizenz aktualisieren**.
1. Klicken Sie auf **OK**. Das Dialogfeld **Info über Citrix Single Sign-On** wird geschlossen.

## Warum sperrt Single Sign-On die Arbeitsstation?

Single Sign-On sperrt die Arbeitsstation, wenn Sie eine Aufgabe ausführen, die ein höheres Sicherheitsniveau erfordert. Zu diesen Aufgaben kann das Ändern oder Anzeigen von Kennwörtern gehören.

Nach der Sperrung der Arbeitsstation prüft Single Sign-On ihre Identität mit dem eingegebenen Kennwort für das Konto. Manchmal müssen Sie sogar die Sicherheitsfragen beantworten. Mit dieser Verifizierung verhindert Single Sign-On, dass andere Personen auf vertrauliche Daten zugreifen.

Dies ist manchmal ärgerlich, dient aber dem Schutz der persönlichen und Unternehmensdaten.

