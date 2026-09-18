# 2. Actifs, émissions et peg Bitcoin

Le premier mécanisme central du dépôt concerne actifs, émissions et peg bitcoin.
Le code reçoit des données structurées, vérifie leurs contraintes puis applique la transition correspondante.
Les types publics fixent la forme des valeurs que les autres composants peuvent transmettre.
Les contrôles locaux empêchent qu’un état incomplet soit accepté comme une opération terminée.
Les valeurs persistantes servent de référence aux appels suivants et aux outils d’observation.
Les erreurs rendent explicites les préconditions qui ne sont pas satisfaites.
Les événements ou sorties exposent les résultats sans remplacer l’état canonique du protocole.
Une intégration doit respecter l’ordre des étapes et les unités utilisées par ces structures.

[Chapitre suivant : Valeurs confidentielles et validation](03-valeurs-confidentielles-et-validation.md)
