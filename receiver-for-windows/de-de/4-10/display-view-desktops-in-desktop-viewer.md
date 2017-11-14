---
layout: leftnav
title: Anzeigen Ihrer Geräte in Desktop Viewer
menu: subnav
---

Citrix Receiver für Windows erkennt die an Ihren Computer angeschlossenen Geräte und ermöglicht Ihnen die Auswahl der Geräte zur Verwendung mit dem gehosteten Desktop und den gehosteten Anwendungen.

* Mit den Einstellungen in **Einstellungen** > **Verbindungen** können Sie anpassen, welche Geräte, z. B. Mikrofone und Webcams, mit der virtuellen Sitzung verbunden werden.
* Mit der lokalen Maschine verbundene Geräte werden in der Geräteliste unter **Einstellungen** > **Geräte angezeigt**.
* Wenn Sie eine Verbindung mit einem Gerät hergestellt haben und es wird nicht in der Liste angezeigt, klicken Sie auf **Aktualisieren**.
* Verbundene Geräte werden als **Optimiert**, **Von Richtlinie eingeschränkt** oder **Allgemein** angezeigt.

| Gerät | Beschreibung |
| --- | --- |
| Optimiert | Das Gerät hat einen virtuellen Citrix Kanal und ist automatisch in der Remotesitzung und auf der lokalen Maschine gleichzeitig verfügbar. In der Spalte "Aktuelle Verbindung" für optimierte Geräte wird angezeigt, dass das Gerät auf der lokalen Maschine und in der **Remotesitzung** verbunden ist. Das Kontrollkästchen "Umleiten" ist aktiviert und kann nicht bearbeitet werden. Mit der Schaltfläche zum Wechseln in der Spalte "Virtueller Kanal" können Sie zwischen "Optimiert" und "Allgemein" wechseln. Wählen Sie beispielsweise "Zu allgemein wechseln", wenn der virtuelle Kanal nicht die volle Funktionalität des Geräts unterstützt. |
| Allgemein | Das Gerät hat keinen virtuellen Citrix Kanal und kann nicht auf der lokalen Maschine und in der Remotesitzung gleichzeitig verwendet werden. Mit dem Kontrollkästchen "Umleiten" können Sie die Verfügbarkeit des Geräts in der Remotesitzung oder auf der lokalen Maschine aktivieren und dazwischen wechseln. Der aktuelle Verbindungsstatus wird in der Spalte "Aktuelle Verbindung"angezeigt. |
| Von Richtlinie eingeschränkt | Der Administrator hat eine Richtlinie festgelegt, um diesen Gerätetyp einzuschränken. Beispielsweise sind USB-Mäuse und -Tastaturen in der Regel durch Richtlinien eingeschränkt, da ihr Verhalten in der Remotesitzung automatisch ohne USB-Unterstützung gehandhabt wird. Andere Geräte, wie Netzwerkgeräte, können aus Sicherheitsgründen eingeschränkt sein. In der Spalte "Aktuelle Verbindung" für von Richtlinien eingeschränkte Geräte wird nur **Lokale Maschine** angezeigt. Sie können das Kontrollkästchen "Umleiten" nicht für von Richtlinien eingeschränkte Geräte aktivieren. |

