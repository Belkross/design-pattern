# Façade

## Pourquoi l’utiliser ?

Faciliter l’accès à une opération complexe qui utilise de nombreuses dépendances.

## Comment faire ?

1. Identifier les entrées nécessaires à l’opération complexe et écrire l’unique méthode publique qui l’exécutera.
2. Documenter toutes les dépendances dans le constructeur
3. Extraire la complexité de la méthode publique dans des méthodes privées

## Notes

Souvent il est pertinent d’appliquer le patron de conception Singleton à une Façade.
