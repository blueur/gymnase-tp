# Projet

Le deuxième test de programmation sera sous forme de projet individuel. 

## But

Créer un petit jeu textuel en Python. 

Le type de jeu est libre mais voici quelques inspirations :
- **Un livre dont vous êtes le héros** : Vous jouez un personnage et décidez de ses actions. Suivant l'action choisie, le personnage va rencontrer différent événements. 
- **Quiz** : Posez une série de question et donnez le score final. 

## Dévelopement

Commencez par faire un plan simple sur papier de votre jeu (organigramme des 2-3 premiers choix). 

Vous pouvez utiliser l'[éditeur Gymnacode](https://gymnacode.web.app/editor){:target="_blank"} ou le logiciel Thonny installé sur les ordinateurs pour écrire votre programme. 

> Faites bien attention d'enregistrer votre travail en cours sur OneDrive pour pouvoir le reprendre la prochaine fois. 
> - Pour enregistrer votre travail sur Gymnacode, cliquez sur "Télécharger", puis mettre le fichier téléchargé sur votre compte OneDrive. 
> - Pour reprendre votre travail sur Gymnacode, cliquez sur "Téléverser", puis sélectionnez la dernière version de votre projet sur OneDrive. 

## Evaluation

### Critères d'acceptation

Tous les critères suivants doivent être remplis pour que le rendu soit accepté (note de 1 sinon) : 

- Le code et l'arbre de décision doivent être rendu à temps
- L'arbre de décision doit avoir une structure différente des exemples
- Tout le code doit ne doit pas être similaire à celui de vos camarades ou à un exemple sur internet (inspirer mais pas copier)

### Critères minimaux

Tous les critères suivants doivent être remplis pour avoir au moins 4 : 

- Le code doit être exécutable sans erreur
- Le code doit contenir au moins 4 embranchements (gérer 4 entrées de l'utilisateur)
- Au moins 3 types d'embranchements différents et au moins deux différents de ceux de l'exemple (oui/non et a/b/c)
- Être capable de justifier chaque ligne de son code (pourquoi tel ou tel choix)

### Critères d'amélioration

Les critères suivants permettent d'atteindre le 6 (une fois que les critères minimaux soient tous validés) :

- 0.5  : Ne pas arrêter le jeu lors d'une entrée invalide (utilisation des boucles)
- 0.5  : Utilisation et bon nommage des fonctions
- 0.5  : Appliquer les [bonnes pratiques PEP 8](https://www.carnets.info/python/pep8/){:target="_blank"} (indentation de 2 espaces acceptée)
- 0.25 : Lisibilité du code (avec éventuellement des commentaires)
- 0.25 : Facile de sélectionner une réponse (en acceptant 'o' pour 'oui' et 'n' pour 'non' par exemple ainsi que les majuscules, voir [lower()](https://www.w3schools.com/python/ref_string_lower.asp){:target="_blank"})

### Critères bonus

Les critères suivants peuvent être considérés en ajoutant des points bonus :

- Le code contient plus d'embranchements et de types significativement différents
- Originalité et/ou complexité de l'histoire
- Le code est particulièrement lisible et descriptif

## Rendu

Les éléments suivants seront à rendre sur Teams dans le devoir "Projet de programmation" avant le **mercredi 10 mai 2023 à 23h59** :
- un fichier .py contenant le code exécutable
- l'arbre de décision du programme (un scan, une photo, un schéma, ...) avec des mots-clefs juste pour avoir une vision globale
- Renommez vos fichiers avec vos prénom et nom, par exemple : `prenom_nom.py`

Après le rendu, il y aura une session individuelle **obligatoire** de question-réponse les **mercredis 17 (groupe B) et 24 (groupe A) mai** avec l'enseignant d'environ 5 minutes pour que vous expliquiez votre démarche et les choix que vous aviez fait. 

> Vos programmes seront testés par vos autres camarades de classe pendant ce temps-là. Si vous ne souhaitez pas partager votre jeu, envoyez-moi un e-mail pour m'en avertir. 

## Exemple

![Courte péripétie](https://kroki.io/plantuml/svg/eNqFj0sOgkAMhvecoku4AixMNHHnI-oFhqGBRiikM4N38hpeTJTHgAmxy7_f96eNL4pzFMgFmVCSwDzI6gLCU2pQ2m6jlViETRRoZbDLHUUBwIhdHbWCHoJuFuBnRnhXYEU8Yh491GxVzuhzgPiGVfN6Wkxm4Z3K8sfd19JRC_OMkrkQoz9mf83C3CrOyJoVETnrP5l9eaw5gmEfn7R2jbJUMxQqJeuwLKf7hyJfsixYl7_ipL0BB7x4xA==)
{% comment %}
:Ranger grenier;
switch (Observer carte ?)
case (Oui)
  switch (Suivre carte ?)
    case (Oui)
      switch (Chemin ?)
        case (Montagne)
          :Tempête;
          kill
        case (Forêt)
          :Perdu(e);
          kill
        case (Chemin)
          :Bandits;
          kill
      endswitch
    case (Non) 
      :Occupation habituelle;
      kill
  endswitch
case (Non) 
  :Occupation habituelle;
  kill
endswitch
{% endcomment %}

- [Version avec if](https://gymnacode.web.app/editor?code=eNq1Vb1u2zAQ3v0UVy9OgLTZDQRFUXQoUKBL0Z2Szs4FNKkcSaHx03Ss%2Bgad9WK9o34sKzbQpaNA8r6f%2B%2B5UM7l4s%2F7kgI3bo3ERGh8ZYc%2FoCPlOPlOA6A8FHiEkhuQQGkKyFqE0HBEqDICuIfYuvIP17arui34tAnKDDNZMN6G2Uq7m7leA93J1VT56%2BgEPQK5O8uZj%2Frzxie6dd7dbLbeiHQzXHmAtR%2BvtCqCemIeNidFwpeSV4Qg3cGc8GH5OQl%2Bp1xhJmJQs9TLZqdIHUcTQ%2FQS7QVfJeRRSFT2nroXa9GX1Vc8b4F%2BYA1zkPmF%2BV4JV15ZUCT%2B1R4jTwMI06GKSXrzJNM8f1SYEeSJNYAy9tULwySd2XYtaQExupZxoanwAs9sZYu1UvAQodayoFqvIDeipwMGgCfnL7NYdmEYdn2q8svs5bcjCC5jcdMLEQbzAAzmh70Ogwgqf7QLjrdzfKp%2BcFDY1ZQRRm7uQHJTeKurBu2j20lJ0Dmnftcs6hdT5bEHsAZMEbgLV16W8VrP6eM5qZSwVNvR857n7HceAOznBJVA5I2y929%2BBGBQGUKtMVXJFux2VJN8yFoaycyFRw2rqYIx4RlB47rvZQ%2Fc5upY3c1%2Fcl1PaFnkzQ9rOo%2BM0WUfVqRQiHuqQ84JcCZdX%2BRDnuTdDXbNTJk6Dw0xN197grUjWK0MShDvqrFPQIxnPkCdQAfVIq2vjMqTbvOjsNjQwm1DQnikqloq%2BsU85h%2FMuRva1Au6RMYVxEcxl6TCfEnDW6tcCs2u5hHqkBVTLLBtRD4KkQxX1N2UWTU4BY5OuqSkv9if49Cj5UCNYNxEOK7nvFMYxNbp3x3kqjKXQteEK%2Bdn%2B1leFkcUWQ07baE0ty0k2oMtyhkl2AnuEgrHqD2c6Ai6o96roMA5ZH8iFYNmMFxZg%2FvUcT78JK2n03R95LJHr2qjDoqRMXityqAvNl2WqTST56cCjKSgmvT4acCJ4nd4Vbv%2BV2cjrKqu%2F%2BUeVIA%3D%3D){:target="_blank"}
- [Version avec while](https://gymnacode.web.app/editor?code=eNq1VU2PEzEMvfdXmLl0VyrsvRJCCHFAQuKCuCAOmRm3NUqTWScZ2P4ajpR%2FwHn%2BGHbmo7PtVtoLl0rT2H5%2Bzy9Ow%2BTiTfHeARu3ReMitD4ywpbREfJKPlOA6PclHiAkhuQQWkKyFqEyHBFqDICuJfYuvILidtH0RT%2BVAblFBmumSGislGu4%2Bx3gjYQuqp2nn%2FAaimLxY0daM%2F%2FhfARy8LXwiYoVFM674tt6ATDGk2uSYLzLnzcSdScht2uFX9BmDJO6WkATm4lpWJoYDddKVhmN7Q1cGfeG75PQVaoNRpLOK5Z6mdxU6a0owND9ArtEV8u5dlzTfeqO0Ji%2BrGb1PE%2BdC1OAZ3F9HluAJ%2FlOfX5RUnV3rKgWTjoCIUtD56ZFF5PM%2B0Wm9jipMSFIijTKGPrxCanvPrHrjqgFZJBHKSc6tD6A2WwMsbohPgUodawoJfIK2x49lTiIOiF%2FnEWtwLQ6panGxYju05IsPIDJxiJMHEQL3JOT9n0IVFrpZ32G8VLi19pPdiObhjKCsM2TSw4qbxV17100W7EBOoe07Y7ndUqp88GCyAMmCdwEqtmVZKtY%2FRWY1cpYSmzwycZz9yeOl8jJCZ4DVbOGrXfbFYhAYQC12qlSrmmzoUqtJVfPUFYuJGpZRR2EEc0ISs%2F9NHvo3kdnHr3iUqMeLfWnGm16zajmrryrJpueGdUUY%2FLcc04teVCBtPeI%2ByZkoyHXQuLCWDIy7lVUue1kptMtZaa2O97grWilIYOFhDTqIqKgR7ILQr7uCqhHWl0nniHd8kEXRUtDZxMK2keMynNGn9mnbOD5%2BCP7RgG3yJjCuHXmtHRznKzzyCOXBLNquYRqpAWUy8xUUQ%2BC2EoZ9ZFyiU22D2ObrrGpnpxP8GknxlIhWNceDu9FPymMo930URgvYmkshe4YrjQ%2Fe1w0qzSyRWPINh2laWSrybp1mc6wApzAHqBkrPvDofrigoju08uNmN%2B7w%2BltsuIy3%2F2VZLFSd4x6exTM5D0jh7rhfFWlxkSSlw52pqSYNLwntrgC%2B19B%2FwEHmp2P){:target="_blank"}
- [Version avec def](https://gymnacode.web.app/editor?code=eNrFVsGO00AMve9XmFzalQp7r4QQQhyQkLggLojDJHFbo3Qm65kJsF%2FDkfAHnPNj2JNJm3QrBCculZKx%2Fez33jitcQdkA7s6VoGcXd9ubwBalnfr4rUFNnaPxgboXGCEPaMl5I08Rg%2FBHUt8AB8ZokXoCKlpECrDAaFGD2g7Ymf9Myhuz2XflR65Q4bGnGKhbaRgy8MPDy9ScHVw9BWeQ1HIw5cDaeH0yrogLcPHwkUqNlBYZ4tP2vU5h2wbBehVelxL3J0E3W7HLmg3xUlxrTHmutzVWmOwWUQpRI6qqtgaZcpL4M1NLfwt3s3o%2B6AcJQIfzqM2w3dwwy9BkIGGPhgKgEKvuY8SJoed8%2FOKcDAlhajhI40Z89TtUi%2B%2FMiEYrlUy1WXCzYoxHg0nJBWsxUDSUsUy51KilwLH2k2zQlvLuVJe030cemjNWFaz%2FpNWpkMbIuO%2Fa3XOvBSqHvqKamFGzSiUUZ5%2FyoAnc4JSSmu8V21RePWjjYWYzy6yHXrUdDF0L8WES5XV7HaGWO9FuAYndRphWyQSykbsWOJSmLezmI1MozqfKjwS%2BT6uqIFvYNL1IozshSk8kviqdd5TKa6C7QLhqURvtZd0I9m0lOrLpEn5aKFyjWIenQ1mLzZCa5H2Q7%2BsUkqVNw0IMWCiQJ0ANbeSXKVpXAKzSglJh8ou2zkefoZpkVg5wSVMNWu2cXa%2FAaHGZ8hGu9Rha9rtqFJfyrXRKyc9%2BEgdK52ZEmGLoHQ8qjgC%2F6W7jXq71J%2Fqz%2FY2d%2BVdddXcJpt24uKatcscI71huBZQFRO4DnQy%2Fbnmpemt2vtBSVdGAh5bn2yLXAs1j2wqJuBRGZWwudgZzNQN%2FRpvhX09znYUGlFXO3k9ks3k0%2FJRMD3SyuqfBGdX33RtdZS7mm28PPRsgvfsYroAcwvJp6xVkD0yRj%2FtvfkYurvO9lv4bDlQYiilKx%2BarL3PTBn0wIstdYIxUq6%2FSQZk7OKs%2B0mRSwG8iwfxo07Lumkxf2hHKTBMLtWv6XRzS9OQH3p%2FpdvZF1kzSiNLO%2Fjk7ImHVtaobHc7fnbGfSF%2FACSrZKzHw9z48o%2FBb1IkvmE%3D){:target="_blank"}

## Plus d'exemples

- [Pendu](https://lesbricodeurs.fr/articles/jeu-du-pendu-python/){:target="_blank"}
- [Aventure](https://www.makeuseof.com/python-text-adventure-game-create/){:target="_blank"}
- [Aventure & Quiz](https://www.derekshidler.com/how-to-create-a-text-based-adventure-and-quiz-game-in-python/){:target="_blank"}

---

[Retour à l'accueil](../README.md)
