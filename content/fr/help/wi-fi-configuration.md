---
title: Comment configurer le réseau Wi-Fi
authors:
  - Nicolas Martignoni
type: kb
date: 2017-08-12
lastmod: 2018-07-31
description: Il est possible de modifier différents réglages du point d'accès WiFi de la MoodleBox.
slug: modification-de-la-configuration-du-reseau-wi-fi
weight: 6
categories:
  - Maintenance
  - Premiers pas

---
En tant qu'administrateur, il est possible de modifier différents réglages du point d'accès sans fils de la MoodleBox. Pour ce faire, visitez [Administration du site > Serveur > MoodleBox][1] dans le bloc d'administration.

{{< figure link="/img/media/wifi-settings-fr.png" thumb="-small" caption="Réglages Wi-Fi" caption-position="bottom" caption-effect="appear" width="550px" >}}

### Changer le nom du réseau Wi-Fi (SSID)

Pour changer le nom du réseau (SSID), saisir un nouveau SSID dans le champ adéquat et cliquer sur le bouton __Changer les réglages Wi-Fi__. À partir de la version 2.3.0 de la MoodleBox, il est possible de choisir un SSID comportant des caractères spéciaux, tels que des emojis, et y compris des espaces.

### Changer le canal Wi-Fi du point d'accès

Pour changer le canal Wi-Fi du point d'accès de la MoodleBox, sélectionner un numéro de canal et cliquer sur le bouton __Changer les réglages Wi-Fi__.

### Changer le pays de régulation du point d'accès sans fils (à partir de la version 2.5.0)

Pour changer le pays de régulation du point d'accès sans fils de la MoodleBox, sélectionner un pays dans la liste déroulante et cliquer sur le bouton __Changer les réglages Wi-Fi__.

{{% notice info %}}
Les canaux Wi-Fi autorisés dépendent du pays de régulation. Suivant le pays choisi, certains canaux ne seront plus disponibles.
{{% /notice %}}

### Retirer le mot de passe du réseau Wi-Fi ou le changer

Pour permettre un accès simplifié au point d'accès sans fils de la MoodleBox, il est possible de permettre son accès sans mot de passe. Pour ce faire, décocher la case __Réseau Wi-Fi protégé par mot de passe__. Ce réglage peut être modifié en tout temps.

Il est également possible de modifier le mot de passe du point d'accès sans fils de la MoodleBox. Pour ce faire, saisir un nouveau mot de passe, composé d'au minimum 8 caractères et au maximum 63 caractères. Si le mot de passe choisi n'est pas valide, le mot de passe par défaut __moodlebox__ sera automatiquement remis.

 [1]: http://moodlebox.home/admin/tool/moodlebox/index.php