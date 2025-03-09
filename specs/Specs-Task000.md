# Spécifications - Evaluation II - Pratique

Vous trouverez dans ce document le *backlog* à traiter durant l'épreuve sommative.

# Consignes

| Critère            | Valeur                                         |
|:-------------------|:-----------------------------------------------|
| Temps à disposition | 45 min                                         |
| Moyens auxiliaires | Tout, sauf le travail collaboratif (IA inclus) |
| Pondération        | 30% de la note du module (avec la théorie)     |

Afin de favoriser une bonne concentration, vous pouvez bien entendu écouter de la musique.

# Déroulement

1) Vous ne recevrez dans un premier temps que le backlog de l'épreuve, sans le code.
2) Nous étudierons ensemble ce contenu puis vous aurez l'occasion de poser des questions.
3) Vous pourrez ensuite "fork" le dépôt et vous mettre au travail.
4) Une heure spécifique sera définie en classe pour d'éventuelles questions.

# Livraison finale

* Durant l'épreuve, rien ne doit être publié sur votre dépôt personnel (qui est publique).
* La livraison du code se fera après le temps imparti, sous la conduite de l'enseignant.
* Seule la branche develop devra être publiée. C'est elle qui contiendra la totalité du travail réalisé.

# Point de départ

Le projet que vous venez de *fork* + *clone* est fonctionnel. Autrement dit après avoir réalisé la commande suivante:

```java
mvn clean spring-boot:run
```

Tomcat écoute bien sur le port 8080 et cette commande :

```bash
curl localhost:8080/employees | jq
```

produit ce résultat:

```
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    97    0    97    0     0    260      0 --:--:-- --:--:-- --:--:--   260
[
  {
    "id": 1,
    "name": "Bilbo Baggins",
    "role": "burglar"
  },
  {
    "id": 2,
    "name": "Frodo Baggins",
    "role": "thief"
  }
]
```

# Critères d'évaluation globaux

Ce tableau est donné à titre d'information. Lors de la correction les pondérations peuvent être modifiés
afin de mieux valoriser vos travaux.

| Critères globaux                                    | Valeur |
|:----------------------------------------------------|:-------|
| La compilation ne produit pas d'erreur              | 3pts   |
| Aucune regression fonctionnelle                     | 3pts   |
| Les exemples d'appels (controller) sont à jour      | 3pts   |
| Les pratiques Git-flow sont suivies                 | 3pts   |
| Les pratiques du *Conventional Commit* sont suivies | 3pts   |
| Les routes retournent bien les JSON demandés        | 3pts   |
| Le minimum de code a été produit                    | 3pts   |
| L'architecture Spring a été respectée               | 3pts   |
| Le code est soigné (bonnes pratiques)               | 3pts   |