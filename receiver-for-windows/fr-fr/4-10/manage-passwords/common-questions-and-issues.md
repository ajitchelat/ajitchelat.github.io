---
layout: leftnav
title: Questions et problèmes communs
menu: subnav
category: Gérer mes mots de passe
---

La liste ci-dessous dresse la liste des questions soulevées par l'utilisation de Single Sign-On ainsi que des problèmes auxquels vous pouvez être confrontés.

## Je reçois un message d'erreur indiquant que mon mot de passe arrive bientôt à expiration

L'un des meilleurs moyens de sécuriser vos informations est de modifier régulièrement votre mot de passe. Sur la base de paramètres définis par votre entreprise, Single Sign-On vous rappelle automatiquement de modifier vos mots de passe quand ils sont en place depuis trop longtemps.

Ces messages continuent à s'afficher tant que vous ne modifiez pas votre mot de passe.

## Je ne souhaite pas exécuter le Single Sign-On maintenant

Il peut vous arriver de ne pas souhaiter l'exécution de Single Sign-On. Par exemple, vous pouvez avoir besoin de travailler sur une page d'ouverture de session sans que Single Sign-On ouvre effectivement une session du programme concerné.

Dans ces instances, utilisez la fonctionnalité Pause de Single Sign-On. La fonctionnalité Pause arrête l'activité d'ouverture de session automatisée tout en maintenant Single Sign-On ouvert et disponible.

## Mon nouveau mot de passe est rejeté par le programme

Vous avez modifié votre mot de passe pour un programme à l'aide de l'assistant de modification de mot de passe. Cependant, lorsque vous essayez d'ouvrir une session de ce programme, votre nouveau mot de passe est considéré incorrect et refusé par le programme.

Ceci est probablement dû au fait que le nouveau mot de passe a été stocké dans Single Sign-On, mais n'a pas été accepté par votre programme. Par conséquent, Single Sign-On soumet un mot de passe incorrect.

Utilisez la fonctionnalité Rétablir le mot de passe précédent pour résoudre ce problème.

**Remarque** : si cette fonctionnalité n'est pas disponible, contactez le service d'assistance technique de votre entreprise.

## Pour rétablir un ancien mot de passe d'un programme

1. Dans la zone de notification Microsoft Windows, généralement située à droite de la barre des tâches, cliquez avec le bouton droit de la souris sur l'icône Citrix Receiver et sélectionnez **Mots de passe** > **Gérer les mots de passe**.
1. Dans la fenêtre Gérer les mots de passe, sélectionnez le programme ou le site Web souhaité et cliquez sur **Modifier**. Une boîte de dialogue contenant les propriétés du programme sélectionné s'affiche.
**Remarque :** il se peut que votre entreprise ait activé un processus de vérification d'identité à ce stade. Si c'est le cas, entrez vos nom d'utilisateur et mot de passe Windows lorsque vous y êtes invité. (Si vous ouvrez une session à l'aide d’une carte à puce ou toute autre méthode d'authentification qui ne requiert pas de nom d'utilisateur et de mot de passe, utilisez ceci pour vérifier votre identité lorsque vous y êtes invité).
1. Cliquez sur **Rétablir le mot de passe précédent** et cliquez sur **Oui** pour confirmer l'action.

## Mes données utilisateur sont inaccessibles

Lorsque vous ouvrez une session sur votre ordinateur, Single Sign-On se connecte au serveur sur lequel votre entreprise stocke ses informations utilisateur Single Sign-On. Si la connexion aboutit et que votre identité est confirmée, Single Sign-On démarre.

Par contre, si la connexion ou l'identification échoue, Single Sign-On ne démarre pas et un message d'erreur peut apparaître, indiquant que l'accès à vos données utilisateur n'a pas pu s'effectuer. Dans ce cas, contactez le service d'assistance informatique de votre entreprise.

## Mon navigateur Web ne fonctionne pas avec le Single Sign-On

Single Sign-On prend uniquement en charge Microsoft Internet Explorer. L'utilisation d'un navigateur Web différent risque de ne pas produire les résultats prévus.

## Le Single Sign-On rouvre ma session alors que je viens de la fermer

Lorsque vous fermez une session d'un programme ou d'un site Web protégé par mot de passe, il arrive que l'écran d'ouverture de session de ce programme s'affiche de nouveau. Suivant la manière dont votre entreprise a configuré Single Sign-On, il se peut alors que le plug-in ouvre de nouveau une session du programme.

Dans ce cas, procédez comme suit :

* Si votre entreprise a mis la fonctionnalité Pause de Single Sign-On à votre disposition, utilisez-la avant de fermer la session.
* Si la fonctionnalité Pause n'est pas disponible, fermez la session du programme, puis fermez rapidement la fenêtre du programme avant que Single Sign-On puisse rouvrir une session.

**Remarque** : contactez le service d'assistance informatique de votre entreprise pour lui expliquer la situation et suggérer à l'administrateur de Single Sign-On d'activer le paramètre de définition d'application de détection avancée consistant à **Ne traiter que la première ouverture de session pour cette application**.

## Dois-je suivre une procédure particulière avant de travailler hors ligne ?

Si votre entreprise a installé Single Sign-On sur votre ordinateur au lieu de l'exécuter sur le réseau de l'entreprise à partir d'un serveur, vous devez actualiser votre licence avant de travailler hors ligne. De cette façon, vous disposez de la totalité du temps alloué par la licence jusqu'à ce que vous vous reconnectiez au réseau de votre entreprise.

## Pour actualiser la licence de Single Sign-On

1. Dans la zone de notification Microsoft Windows, généralement située à droite de la barre des tâches, cliquez avec le bouton droit de la souris sur l'icône Citrix Receiver et sélectionnez **Mots de passe** > **Gérer les mots de passe**.
**Remarque :** il se peut que votre entreprise ait activé un processus de vérification d'identité à ce stade. Si c'est le cas, entrez vos nom d'utilisateur et mot de passe Windows lorsque vous y êtes invité. (Si vous ouvrez une session à l'aide d’une carte à puce ou toute autre méthode d'authentification qui ne requiert pas de nom d'utilisateur et de mot de passe, utilisez ceci pour vérifier votre identité lorsque vous y êtes invité).
1. Cliquez sur À propos. La fenêtre À propos de Citrix Single Sign-On s'affiche.
1. Cliquez sur **Actualiser les licences**.
1. Cliquez sur **OK**. La fenêtre **À propos de Citrix Single Sign-On** se ferme.

## Pourquoi le Single Sign-On verrouille-t-il ma machine de travail ?

Single Sign-On verrouille votre machine de travail chaque fois que vous tentez d'effectuer une tâche requérant un niveau de sécurité supplémentaire. Il peut s'agir de tâches comme la modification ou la révélation d'un mot de passe.

Lorsque votre machine de travail est verrouillée, vous devez faire vérifier votre identité par Single Sign-On en fournissant le mot de passe de votre compte. Dans certains cas, vos réponses aux questions de sécurité peuvent également vous être demandées. Par une telle vérification, Single Sign-On empêche autrui d'accéder à vos informations sensibles.

Ces contrôles pouvant sembler contraignants ont pour objectif de vous protéger, vous, vos données et votre entreprise.

