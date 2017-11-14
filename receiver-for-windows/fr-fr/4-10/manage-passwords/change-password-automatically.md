---
layout: leftnav
title: Modifier votre mot de passe automatiquement
menu: subnav
category: Gérer mes mots de passe
---

L'assistant de modification de mot de passe automatise le processus de modification de votre mot de passe sur les programmes identifiés. Suivant la manière dont votre entreprise configure Single Sign-On, il se peut que vous puissiez créer votre propre mot de passe ou laisser Single Sign-On en créer un pour vous.

**Remarque :** Étant donné que les mots de passe générés par l'assistant de modification de mot de passe consistent en groupements aléatoires de lettres, nombres et autres caractères, leur niveau de sécurité est très élevé. Envisagez cette méthode car Single Sign-On gère les mots de passe et vous n'avez pas besoin de les mémoriser.

Suivant la configuration effectuée par l'entreprise, l'assistant de modification de mot de passe démarre d'une des façons suivantes :

* lorsque votre programme indique que votre mot de passe doit être modifié ;
* lorsque vous démarrez le processus de modification de mot de passe du programme.

Dans certaines instances, il se peut que Single Sign-On ne détecte pas le processus de modification de mot de passe et ne démarre pas l'assistant. Dans ce cas, vous devez modifier votre mot de passe manuellement à la fois dans le site Web ou dans le programme et dans Single Sign-On pour vous assurer que les mots de passe correspondent.

## Choisir la méthode de création de votre nouveau mot de passe

Si votre entreprise rend cette fonctionnalité disponible, la page **Choisissez la méthode de création de votre nouveau mot de passe** de l'assistant de modification de mot de passe permet de choisir la méthode de création de votre nouveau mot de passe. Les options sont les suivantes :

* **Choisir un mot de passe généré par le système** : Lorsque vous sélectionnez cette option et que vous cliquez sur **Suivant**, l'assistant de modification de mot de passe crée un mot de passe hautement sécurisé. Le mot de passe ne vous est pas révélé pendant ce processus car il est stocké dans Single Sign-On et vous n'avez pas besoin de le connaître. Toutefois, si votre entreprise configure Single Sign-On de façon à le permettre, vous pouvez voir le mot de passe après avoir quitté l'assistant, si vous le souhaitez.

**Remarque** : Étant donné que les mots de passe générés par l'assistant de modification de mot de passe consistent en groupements aléatoires de lettres, nombres et autres caractères, leur niveau de sécurité est très élevé. Envisagez cette méthode car Single Sign-On gère les mots de passe et vous n'avez pas besoin de les mémoriser.

* **Créer votre propre mot de passe** : Si vous sélectionnez cette option et que vous cliquez sur **Suivant**, l'assistant de modification de mot de passe vous permet de créer et de soumettre votre propre mot de passe. Ce dernier doit respecter toutes les stratégies de mot de passe définies par votre entreprise en ce qui concerne la taille, la complexité et d'autres facteurs pouvant avoir une incidence sur la sécurité.

## Attendre la confirmation

La page **En attente de confirmation** s'affiche pendant que l'assistant de modification de mot de passe vérifie si la modification de mot de passe a abouti ou échoué.

Si vous déterminez que la modification de mot de passe a abouti avant que l'assistant de modification de mot de passe ferme la page **En attente de confirmation**, cliquez sur **Ignorer** pour passer à la page **Confirmer la modification**.

## Confirmer le changement de mot de passe

La page Confirmer la modification de l'assistant de modification de mot de passe peut s'afficher si elle est activée par votre entreprise. Dans ce cas, vous êtes invité à déterminer si la modification de mot de passe a abouti. Les trois options suivantes sont proposées.

* **Oui** : L'absence de fenêtre de réinitialisation de mot de passe de programme ou un message de réussite indiquent que le mot de passe a bien été modifié. En sélectionnant **Oui** et en cliquant sur **Suivant**, vous indiquez à l'assistant de modification de mot de passe que la modification de votre mot de passe a abouti. Le processus de l'assistant s'arrête.

* **Non** : La présence continue de la fenêtre de réinitialisation de mot de passe de programme ou un message d'échec indiquent que le mot de passe n'a pas été modifié. En sélectionnant **Non**, puis en cliquant sur **Suivant**, vous indiquez à l'assistant de modification de mot de passe que votre programme n'a pas accepté votre nouveau mot de passe. Le processus de l'assistant s'arrête sans modifier votre mot de passe.

* **Je ne sais pas** : Si vous sélectionnez**** cette option et que vous cliquez sur **Suivant**, la page qui s'affiche explique comment déterminer si la modification de mot de passe a abouti. Si vous avez créé votre propre mot de passe, vous pouvez également déterminer la réussite de l'assistant en mettant Single Sign-On sur pause et en ouvrant une session du programme avec le nouveau mot de passe.

**Remarque** : il se peut que vous deviez déplacer la fenêtre de l'assistant de modification de mot de passe pour voir si la fenêtre de réinitialisation de mot de passe de votre programme est toujours ouverte ou si le programme a affiché des commentaires relatifs au mot de passe.

## Confirmer l'échec de modification du mot de passe

La page **Mot de passe inchangé** s'affiche si l'assistant de modification de mot de passe détecte que le changement de mot de passe n'a pas abouti ou si vous avez sélectionné **Non** dans la page **Confirmer la modification**.

La page **Mot de passe inchangé** propose les deux solutions suivantes.

* **Essayer un autre mot de passe** : Utilisez cette option uniquement si le formulaire de modification de mot de passe du programme est encore ouvert. Si vous l'utilisez après la fermeture du formulaire, les mots de passe de votre programme et de Single Sign-On risquent de ne pas correspondre. En sélectionnant **Essayer un autre mot de passe** et en cliquant sur **Suivant** , vous pouvez essayer de soumettre un autre mot de passe au programme. Suivant la manière dont votre entreprise a configuré l'assistant de modification de mot de passe, il se produit l'un des événements suivants :
   * La page Choisir la méthode de création de votre nouveau mot de passe s'affiche. Vous pouvez y opter pour un mot de passe généré par le système ou créer votre propre mot de passe.
   * La page Créer votre propre mot de passe s'affiche.
   * Un mot de passe généré par le système est créé et soumis. L'assistant de modification de mot de passe demande alors de confirmer si le changement de mot de passe a été réussi.

* Quitter l’assistant sans autre action. Cette option **Quitter l'assistant sans autre action** met fin aux tentatives de modification du mot de passe du programme. Vous pouvez toutefois redémarrer l'assistant de modification de mot de passe et réessayer ultérieurement.

## Quitter l’assistant sans autre action

La page Mot de passe inchangé de l'assistant de modification de mot de passe s'affiche si le changement de mot de passe n'a pas abouti ou si vous avez sélectionné **Non** dans la page **Confirmer la modification**.

Si l'assistant de modification de mot de passe a échoué, essayez les méthodes suivantes.

* Cliquez sur **Terminer** dans la page **Mot de passe inchangé** pour quitter l'assistant, puis redémarrez l'assistant pour réessayer.
* Modifiez le mot de passe manuellement dans le programme et dans Single Sign-On.
* Contactez le service d'assistance informatique de votre entreprise.

## Quitter l'assistant lorsque la modification du mot de passe a réussi

La page **Modification du mot de passe réussie** s'affiche si l'assistant de modification de mot de passe détecte que le changement de mot de passe a abouti ou si vous avez sélectionné **Oui** dans la page **Confirmer la modification**.

À ce stade, votre nouveau mot de passe est accepté par le programme et stocké dans Single Sign-On.

## Déterminer si le programme a accepté le nouveau mot de passe

Lorsque vous sélectionnez **Je ne sais pas** et que vous cliquez sur **Suivant** dans la page **Confirmer la modification**, une page expliquant comment déterminer la réussite ou l'échec du changement de mot de passe s'affiche.

Vous pouvez également déterminer la réussite de l'assistant en mettant Single Sign-On en pause et en ouvrant une session du programme avec le nouveau mot de passe.

Si vous cliquez sur **Suivant** sur cette page, la page **Confirmer la modification** réapparaît.

## Créer votre propre mot de passe

La page **Créer votre propre mot de passe** de l'assistant de modification de mot de passe s'affiche si vous avez sélectionné Créer votre propre mot de passe dans la page **Choisissez la méthode de création de votre nouveau mot de passe**. Cette page peut ne pas s'afficher si votre entreprise ne vous a pas donné la possibilité de créer vos propres mots de passe.

Pour éviter de soumettre un mot de passe mal orthographié, vous devez taper le mot de passe dans les zones **Nouveau mot de passe** et **Confirmer**. L'assistant de modification de mot de passe vous permet de savoir si les mots de passe ne correspondent pas. Si les mots de passe correspondent, le bouton **Suivant** devient disponible.

L'assistant de modification de mot de passe requiert de respecter les stratégies de mot de passe établies par l'entreprise. Exemples de stratégies possibles :

* Les anciens mots de passe ne peuvent pas être réutilisés.
* Les mots de passe doivent contenir un mélange de nombres et de lettres.
* Les mots de passe ne peuvent pas inclure certains caractères.
* Les mots de passe doivent respecter une certaine longueur.

