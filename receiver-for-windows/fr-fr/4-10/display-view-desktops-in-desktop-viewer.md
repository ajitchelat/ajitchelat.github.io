---
layout: leftnav
title: Afficher vos périphériques dans Desktop Viewer
menu: subnav
---

Citrix Receiver pour Windows détecte les périphériques que vous avez connectés à votre ordinateur et vous permet de choisir les périphériques à utiliser avec vos applications et bureaux hébergés.

* Vous pouvez utiliser les paramètres dans **Préférences** > **Connexions** pour autoriser ou refuser la connexion de certains périphériques (micro et webcams) à votre session virtuelle.
* Les périphériques connectés à la machine locale sont affichés dans la liste des périphériques dans **Préférences** > **Périphériques**.
* Si vous avez connecté un périphérique et qu'il ne s'affiche pas dans la liste des périphériques, cliquez sur **Actualiser**.
* Une fois connectés, les appareils affichent l'état suivant : **Optimisé**, **Restreint par une stratégie** ou **Générique**.

| Appareil | Description |
| --- | --- |
| Optimisé | Le périphérique dispose d'un canal virtuel Citrix et il est automatiquement disponible à la fois dans la session distante et sur la machine locale. La colonne Connexion en cours pour les périphériques optimisés indique que le périphérique est connecté à la machine locale et à la **session distante**. La case à cocher Rediriger est sélectionnée et ne peut pas être décochée. Vous pouvez basculer entre Optimisé et Générique à l'aide du bouton Basculer en mode générique/optimisé dans la colonne Canal virtuel. À titre d'exemple, sélectionnez Basculer en mode générique si le canal virtuel ne prend pas en charge l'ensemble des fonctionnalités du périphérique. |
| Générique | Le périphérique ne dispose pas d'un canal virtuel Citrix et ne peut pas être utilisé simultanément sur la machine locale et la session distante. Sélectionnez la case Rediriger pour activer/désactiver la disponibilité du périphérique sur une session distante et une machine locale. Vous pouvez voir l'état de la connexion actuelle dans la colonne Connexion en cours. |
| Restreint par une stratégie | L'administrateur a défini une stratégie afin de restreindre ce type de périphérique. À titre d'exemple, les claviers et souris USB sont généralement restreints par défaut par une stratégie car leur comportement est géré automatiquement dans la session distante sans prise en charge USB. D'autres périphériques, tels que des périphériques réseau, peuvent être restreints pour des raisons de sécurité. La colonne Connexion en cours des périphériques restreints par une stratégie affiche uniquement **Machine locale**. Vous ne pouvez pas sélectionner la case Rediriger pour des périphériques restreints par une stratégie. |

