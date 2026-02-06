# Construction de Graphe de Connaissances avec des LLM

[cite_start]Ce projet de recherche est mené au sein du **LIP6 (Sorbonne Université)** dans l'équipe Bases de Données[cite: 7]. [cite_start]Il explore l'utilisation des modèles de langage de grande taille (LLM) pour automatiser la création de graphes de connaissances à partir de corpus historiques complexes[cite: 5, 17].

## 📖 Contexte
[cite_start]Un Graphe de Connaissance (GC) organise l'information en représentant des entités, leurs attributs et leurs relations sous une forme interconnectée[cite: 11]. [cite_start]Plutôt que d'utiliser des pipelines d'extraction rigides, ce projet s'appuie sur la puissance générative des LLM pour transformer du texte brut en représentations sémantiques exploitables[cite: 17, 18].



## 🎯 Objectifs du Projet
[cite_start]Le stage porte sur les données de **Studium** (XIIe - XVIe siècle), regroupant 15 000 fiches sur les membres de l'Université de Paris[cite: 21, 22].
* [cite_start]**Extraction flexible** : Identifier les entités et relations via des techniques de *Prompt Engineering* (Few-Shot, Chain-of-Thought)[cite: 19, 25].
* [cite_start]**Approches de structuration** : Comparer une approche guidée par une ontologie (OWL/RDF) et une approche sans schéma avec normalisation via DBpedia[cite: 24, 29, 30].
* [cite_start]**Consolidation** : Fusionner les instances, gérer les ambiguïtés et attribuer des poids aux relations[cite: 31, 32].
* [cite_start]**Exploitation** : Déploiement dans **Neo4j** et comparaison avec le *Neo4j LLM Knowledge Graph Builder*[cite: 34, 36].

## 🛠️ Stack Technique
* [cite_start]**Langage** : Python (traitement de données et intégration API)[cite: 37].
* [cite_start]**IA & NLP** : OpenAI API, HuggingFace, Prompt Engineering[cite: 38].
* [cite_start]**Graphes** : Neo4j, Cypher, RDF, SPARQL[cite: 6, 33, 39].
* [cite_start]**Modélisation** : Ontologies OWL[cite: 29, 40].

## 🚀 Méthodologie d'Extraction
1. [cite_start]**Identification des Entités** : Utilisation de l'Auto-Réflexion pour améliorer la couverture des données extraites[cite: 25].
2. [cite_start]**Prédiction des Relations** : Application du raisonnement *Chain-of-Thought* pour garantir la qualité des liens sémantiques[cite: 26].
3. [cite_start]**Contrôle Qualité** : Évaluation de la performance via les métriques de Précision, Rappel et F1-score[cite: 33].

## 👥 Encadrement (LIP6)
* [cite_start]**Camelia CONSTANTIN** (Équipe BD) [cite: 8]
* [cite_start]**Raphaël FOURNIER-S'NIEHOTTA** (Équipe ComplexNetworks) [cite: 9, 10]

---
*Projet réalisé dans le cadre d'un stage à Sorbonne Université.*