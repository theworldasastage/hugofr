---
title: "Lovable"
tags: 
  - productivity
---


# Lovable

## Résumé

- **Utile pour :** Créer un site web complet sans aucune connaissance (y compris avec des interactions).
- **Prix :** Free tier puis payant et commence à 25$/mois
- **Type :** Application Web
- **Sensibilité des données :** données transitent vers un cloud inconnu. Ne donc pas y partager des données sensibles
- **Compatibilité :** tout OS 
- **Langues** : Anglais, Français et plus. Interface en anglais
- **Lien de téléchargement :** https://lovable.dev/


## Présentation

{{< image name="images/LovableMain.png" >}}

Lovable est une application qui mélange IA générative et No-Code (le fait de pouvoir créer des outils sans développer.). Son principe est très simple : vous décrivez le site web, l'outil dont vous avez besoin et il vous crée le site web correspondant.

Ensuite le prompt est encore là pour ajuster. Par exemple, je lui ai donné le prompt suivant : 

> Peux tu créer un site web pour promouvoir l'usage des outils d'IA et no-code pour accélerer les processus

Et il m'a généré la page visible ici : [https://ai-power-flow.lovable.app/](https://ai-power-flow.lovable.app/)

{{< image name="images/LovableExample.png" >}}

Le site peut ensuite être adapté via le chat ou en éditant le code pour correspondre exactement aux besoins.

Et bien sur cela utilise les modèles classiques d'IA génératives donc niveau contenu on peut aussi bien [demander du contenu technique](https://ai-power-flow.lovable.app/orthophoto-technique) que commercial.

{{< image name="images/LovableOrtho.png" >}}

## De l'interactivité
Un des usages les moins envisagés est pour créer rapidement des interfaces. Par exemple imaginons que l'on veut faire une interface où l'on rentre quelques informations et il nous retourne un fichier XML (donc pénible à éditer à la main) avec les mêmes informations représentées selon les besoins d'un logiciel. Lovable peut le faire facilement.

> Prompt : Peux tu faire une page web avec un formulaire ou j'entre "Nom", "Prénom", "numéro de téléphone" et où je peux télecharger un XML avec ces informations dans une balise principale "identity" et des sous balises "fullName" (qui combine nom et prénom avec un espace) et "phone"

{{< image name="images/LovableXML.png" >}}

Et notez que dans ce cas, il n'y a pas d'informations envoyées en ligne vu que le calcul du XML est fait en local. Donc même si la création de l'outil pose des questions de sensibilité, son utilisation beaucoup moins.

## Open Source et interconnexion
Le code de l'application créée est intégralement disponible et modifiable au besoin (si vous en avez les compétences).

L'outil est aussi capable de discuter avec d'autres outils dont [Supabase](https://supabase.com/), un autre outil de base de données, qui permet alors d'avoir des informations qui restent (utilisateurs, ajout de documents, etc.)

Cela en fait un outil parfait de prototypage et/ou d'automatisation et simplification de flux de travail!


