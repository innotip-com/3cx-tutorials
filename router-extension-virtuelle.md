## Comment router vos appels en utilisant une "extension virtuelle"

### Principe de base

Les routages par défaut sur 3CX permettent d'orienter les appels directement à leur arrivée, grace aux règles entrantes. Par la suite, on peut donc gérer le routage par "heure de bureau". Cela permet par exemple de router les appels vers un répondeur numérique (IVR ou SVI - Service Vocal Intéractif).

Malheureusement, ce routage ne permet pas d'avoir des routages "fins" du type "j'active l'accueil du standard" ou "le service comptabilité n'est plus disponible".

Afin de faire cela, une astuce est l'utilisation d'extension virtuelle que nous allons détailler ici.

### Mise en place de l'extension virtuelle et son usage

#### Création de l'extension

Pour créer l'extension, il va falloir tout simplement créer une extension.

'''**Astuce** : Vous pouvez réserver une plage de numéros pour les extensions virtuelles, disons par exemple 3XX sur une numérotation à 3 chiffres, avec les extensions utilisateurs en 1XX dans l'exemple qui va suivre'''

#### Mise en place du routage de l'extension

#### Paramétrage du webclient utilisateur pour activer l'affichage des extensions non enregistrées

#### Paramétrage avancé : les groupes
