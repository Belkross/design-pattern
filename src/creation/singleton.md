# Singleton

## Pourquoi l’utiliser ?

Garantir l’existance d’une unique instance de classe.

## Comment faire ?

1. Ajouter une propriété privée statique `instance` qui vaut la classe
2. Créer une méthode publique statique `getInstance`. Elle retourne l’instance et la crée si elle n’existe pas
3. Rendre le constructeur privé et l’écrire
4. Si besoin de paramètres pour initialiser l’instance, créer une méthode publique statique `initialize`

## Notes

La méthode `getInstance` du Singleton ne doit pas recevoir de paramètres en entrée.  
Lorsqu’un Singleton ne nécessite pas de paramètre en entrée, l’initialisation est automatique et implicite. Autrement elle est manuelle.
