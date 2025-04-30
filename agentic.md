Étape 1 : Prise de question utilisateur
→ Agent 1 : Générer Cypher de base

Étape 2 : Analyse syntaxique du Cypher généré
→ Agent 2 : Vérifier la syntaxe Cypher
(si erreur -> corriger automatiquement + retour étape 1bis)

Étape 3 : Envoi de la requête validée à Neo4j
→ Agent 3 : Exécuter

Étape 4 : Si erreur d'exécution liée aux données
→ Agent 4 (facultatif) : reformuler la requête (ex. problème de casse)
