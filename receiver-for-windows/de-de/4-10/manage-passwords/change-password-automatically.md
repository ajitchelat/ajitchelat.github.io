---
layout: leftnav
title: Automatisches Ändern des Kennworts
menu: subnav
category: Verwalten von Kennwörtern
---

Der Assistent für Kennwortänderungen automatisiert das Ändern der Kennwörter für angegebene Programme. Abhängig von der Single Sign-On-Konfiguration im Unternehmen können Sie ein eigenes Kennwort erstellen oder Single Sign-On erstellt ein Kennwort für Sie.

**Notiz:** Da die vom Assistenten für Kennwortänderungen erstellten Kennwörter aus willkürlichen Buchstaben-, Ziffern- und anderen Zeichengruppen bestehen, ist die Sicherheit dieser Kennwörter sehr hoch. Da die Kennwörter von Single Sign-On verwaltet werden, und Sie sich die Kennwörter nicht merken müssen, sollten Sie die Verwendung dieses Features erwägen.

Abhängig von der Konfiguration im Unternehmen wird der Assistent für Kennwortänderungen folgendermaßen gestartet:

* Wenn das Programm angibt, dass das Kennwort geändert werden muss.
* Wenn Sie das Verfahren zur Kennwortänderung des Programms starten.

Manchmal erkennt Single Sign-On die Kennwortänderung nicht, und der Assistent für Kennwortänderungen wird nicht gestartet. In diesen Situationen müssen Sie das Kennwort sowohl auf der Website oder im Programm als auch in Single Sign-On manuell ändern, um sicherzustellen, dass die Kennwörter übereinstimmen.

## Auswählen der Erstellungsmethode für das neue Kennwort

Wenn das Unternehmen das Feature zur Verfügung stellt, können Sie im Assistenten für Kennwortänderungen auf der Seite **Erstellungsmethode für das neue Kennwort** wählen, wie das neue Kennwort erstellt wird. Es gibt folgende Optionen:

* **Systemgeneriertes Kennwort auswählen** Wenn Sie diese Option auswählen und auf **Weiter** klicken, erstellt der Assistent für Kennwortänderungen ein sehr sicheres Kennwort. Dieses Kennwort wird Ihnen nicht beim Erstellen angezeigt, da es in Single Sign-On gespeichert ist und Sie das Kennwort nicht kennen müssen. Wenn das Unternehmen die Option in Single Sign-On aktiviert hat, können Sie das Kennwort anzeigen, wenn Sie den Assistenten beendet haben.

**Hinweis:** Da die vom Assistenten für Kennwortänderungen erstellten Kennwörter aus willkürlichen Buchstaben-, Ziffern- und anderen Zeichengruppen bestehen, ist die Sicherheit dieser Kennwörter sehr hoch. Da die Kennwörter von Single Sign-On verwaltet werden, und Sie sich die Kennwörter nicht merken müssen, sollten Sie die Verwendung dieses Features erwägen.

* **Erstellen eines eigenen Kennworts**: Wenn Sie diese Option auswählen und auf **Weiter** klicken, können Sie im Assistenten für Kennwortänderungen ein eigenes Kennwort erstellen und senden. Dieses Kennwort muss die im Unternehmen geltenden Kennwortrichtlinien hinsichtlich Länge, Komplexität und anderen Faktoren einhalten, die sich auf die Sicherheit auswirken können.

## Warten auf Bestätigung

Die Seite **Warten auf Bestätigung** im Assistenten für Kennwortänderungen wird angezeigt, während der Assistent ermittelt, ob die Kennwortänderung erfolgreich war oder fehlgeschlagen ist.

Wenn Sie erkennen, dass die Kennwortänderung erfolgreich war, bevor der Assistent für Kennwortänderungen die Seite **Warten auf Bestätigung** schließt, klicken Sie auf **Überspringen**, um auf die Seite **Kennwortänderung bestätigen** zu gehen.

## Bestätigen eines geänderten Kennworts

Abhängig von der Konfiguration im Unternehmen wird die Seite Kennwortänderung bestätigen im Assistenten für Kennwortänderungen angezeigt. Wenn die Seite angezeigt wird, müssen Sie feststellen, ob die Kennwortänderung erfolgreich war. Drei Optionen stehen zur Verfügung.

* **Ja**: Wenn das Dialogfeld zum Zurücksetzen des Programmkennworts nicht oder eine Erfolgsmeldung angezeigt wird, war die Kennwortänderung erfolgreich. Wählen Sie **Ja** und klicken Sie auf **Weiter**, um dem Assistenten für Kennwortänderungen anzugeben, dass die Kennwortänderung erfolgreich war. Der Assistent wird beendet.

* **Nein**: Wenn das Dialogfeld zum Zurücksetzen des Programmkennworts oder eine Fehlermeldung angezeigt wird, war die Kennwortänderung nicht erfolgreich. Wählen Sie **Nein** und klicken Sie auf **Weiter**, um dem Assistenten für Kennwortänderungen anzugeben, dass das Programm das neue Kennwort nicht akzeptiert hat. Der Assistent wird ohne Ändern des Kennwortes beendet.

* **Unbekannt**: Bei Auswahl von **Unbekannt** und Klicken auf **Weiter** wird eine Seite angezeigt, auf der beschrieben wird, wie Sie ermitteln, ob das Kennwort erfolgreich geändert wurde. Wenn Sie ein eigenes Kennwort erstellt haben, können Sie feststellen, ob der Assistent erfolgreich war, wenn Sie Single Sign-On anhalten und sich mit dem neuen Kennwort am Programm anmelden.

**Hinweis:** Sie müssen das Dialogfeld des Assistenten für Kennwortänderungen ggf. verschieben, um zu sehen, ob das Dialogfeld zum Zurücksetzen des Programmkennworts oder anderes kennwortbezogenes Feedback angezeigt wird.

## Bestätigen eines nicht geänderten Kennworts

Die Seite **Kennwort wurde nicht geändert** wird angezeigt, wenn der Assistent für Kennwortänderungen erkennt, dass die Kennwortänderung nicht erfolgreich war, oder Sie **Nein** auf der Seite **Kennwortänderung bestätigen** gewählt haben.

Auf der Seite **Kennwort wurde nicht geändert** stehen zwei Optionen zur Verfügung:

* **Anderes Kennwort versuchen**: Verwenden Sie diese Option, wenn das Kennwortänderungsformular des Programms noch geöffnet ist. Wenn Sie die Option nach dem Schließen des Formulars verwenden, stimmen die Kennwörter im Programm und in Single Sign-On ggf. nicht überein. Wenn Sie **Anderes Kennwort versuchen** wählen und auf **Weiter** klicken, können Sie ein anderes Kennwort an das Programm senden. Abhängig von der Einrichtung des Assistenten für Kennwortänderungen im Unternehmen geschieht Folgendes:
   * Die Seite "Auswählen der Erstellungsmethode für das neue Kennwort" wird angezeigt. Sie können zwischen einem systemgenerierten oder einem eigenen Kennwort wählen.
   * Die Seite "Eigenes Kennwort erstellen" wird angezeigt.
   * Ein systemgeneriertes Kennwort wird erstellt und gesendet. Der Assistent für Kennwortänderungen versucht dann zu bestätigen, dass die Kennwortänderung erfolgreich war.

* Assistenten ohne weitere Aktion beenden Bei der Auswahl von **Assistenten ohne weitere Aktion beenden** wird nicht länger versucht, das Kennwort des Programms zu ändern. Sie können den Assistenten für Kennwortänderungen neu starten und es zu einem späteren Zeitpunkt erneut versuchen.

## Assistenten ohne weitere Aktion beenden

Die Seite "Kennwort wurde nicht geändert" des Assistenten für Kennwortänderungen wird angezeigt, wenn das Ändern des Kennworts fehlgeschlagen ist oder Sie auf der Seite **Kennwortänderung bestätigen** auf **Nein** geklickt haben.

Wenn der Assistent für Kennwortänderungen fehlgeschlagen ist, versuchen Sie das Kennwort folgendermaßen zu ändern:

* Klicken Sie auf der Seite **Kennwort wurde nicht geändert** auf **Fertig stellen**, um den Assistenten zu beenden. Starten Sie den Assistenten dann neu.
* Ändern Sie das Kennwort manuell im Programm und in Single Sign-On.
* Wenden Sie sich an den Helpdesk.

## Beenden des Assistenten nach einer erfolgreichen Kennwortänderung

Die Seite **Kennwort wurde geändert** wird angezeigt, wenn der Assistent für Kennwortänderungen erkennt, dass die Kennwortänderung erfolgreich war, oder Sie auf der Seite **Kennwortänderung bestätigen** auf **Ja** geklickt haben.

Das neue Kennwort ist jetzt vom Programm akzeptiert und wird in Single Sign-On gespeichert.

## Prüfen der Akzeptanz des neuen Kennworts vom Programm

Bei Auswahl von **Unbekannt** und Klicken auf **Weiter** auf der Seite **Kennwortänderung bestätigen** wird eine Seite angezeigt, auf der beschrieben wird, wie Sie ermitteln, ob das Kennwort erfolgreich geändert wurde.

Sie können feststellen, ob der Assistent erfolgreich war, wenn Sie Single Sign-On anhalten und sich mit dem neuen Kennwort am Programm anmelden.

Wenn Sie auf dieser Seite auf **Weiter** klicken, wird die Seite **Kennwortänderung bestätigen** erneut angezeigt.

## Erstellen eines eigenen Kennworts

Im Assistenten für Kennwortänderungen wird die Seite **Eigenes Kennwort erstellen** angezeigt, wenn Sie auf der Seite **Auswählen der Erstellungsmethode** für das neue Kennwort die Option "Eigenes Kennwort erstellen" wählen. Diese Seite wird nur angezeigt, wenn Sie eigene Kennwörter erstellen können.

Um einen Schreibfehler beim Kennwort zu vermeiden, müssen Sie das Kennwort in die Felder **Neues Kennwort** und **Neues Kennwort bestätigen** eingeben. Der Assistent für Kennwortänderungen sagt Ihnen, wenn die Kennwörter nicht übereinstimmen. Wenn die Kennwörter übereinstimmen, steht die Schaltfläche **Weiter** zur Verfügung.

Der Assistent für Kennwortänderungen stellt sicher, dass Sie die Kennwortrichtlinien des Unternehmens einhalten. Beispiele für Unternehmensrichtlinien sind:

* Altes Kennwort darf nicht wiederholt werden.
* Kennwörter müssen aus Ziffern und Buchstaben bestehen.
* Kennwörter dürfen bestimmte Zeichen nicht enthalten.
* Kennwörter müssen eine bestimmte Länge haben.

