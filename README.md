# GDPVal — repère d'évaluation (version éducative)

## En une phrase

Ce dépôt montre si un assistant IA peut accomplir des tâches professionnelles réelles — de bout en bout — dans des domaines aussi variés que la finance, l'immobilier ou le gouvernement.

## Pour qui

- Dirigeants / décideurs
- Curieux non techniques
- Développeurs qui veulent comprendre « ce qu'on mesure » plutôt que « comment coder »

## Ce que ce dépôt permet de faire (et ce qu'il ne permet pas)

### Permet
- Observer des exemples concrets de tâches accomplies par un assistant IA dans 9 secteurs d'activité.
- Comparer la qualité des livrables produits par l'IA à ce que ferait un professionnel humain expérimenté.
- Comprendre quels types de travaux semblent accessibles à l'IA aujourd'hui.

### Ne permet pas
- Ne garantit pas que l'IA sera performante dans votre contexte ou sur vos propres données.
- Ne remplace pas une évaluation humaine sérieuse avant toute décision d'adoption.
- Ne prédit pas les résultats futurs : ce que l'IA sait faire évolue rapidement.

## Pourquoi ça compte (utile pour décider)

- **Prioriser** : identifier quelles tâches répétitives ou documentaires pourraient être automatisées en premier.
- **Réduire les risques** : voir concrètement où l'IA échoue encore, pour ne pas la déployer à mauvais escient.
- **Saisir les opportunités** : certains secteurs (immobilier, gouvernement, biotech) montrent des résultats déjà exploitables.

## Comment le lire (chemin de lecture)

1. Commencer par [« Ce que ça mesure »](docs/what-it-measures.md)
2. Puis [« Comment interpréter les résultats »](docs/how-to-read-results.md)
3. Puis [« Limites et points d'attention »](docs/limits.md)
4. Enfin explorer le dossier `outputs/` pour voir les exemples concrets

## Ce que ça mesure (sans jargon)

Une « tâche utile » ici, c'est un livrable professionnel réel : un formulaire rempli, un planning hebdomadaire, un scénario, un document juridique… Pas un résumé, pas une réponse à une question — un document complet, utilisable tel quel.

Ce dépôt sert à observer si un assistant IA arrive à **terminer une tâche de A à Z**, pas juste à produire du texte. Il part d'une consigne, analyse des fichiers de référence, et rend un document finalisé.

→ Pour aller plus loin : [docs/what-it-measures.md](docs/what-it-measures.md)

## Comment interpréter les résultats

Quatre critères simples pour juger chaque livrable :

1. **Réussite** — La tâche est-elle terminée ? Le document est-il complet et cohérent ?
2. **Qualité** — Le contenu est-il juste, professionnel, utilisable sans retouche majeure ?
3. **Effort humain** — Combien de temps faudrait-il à un humain pour corriger ou valider ?
4. **Risques** — Y a-t-il des erreurs factuelles, des oublis ou des formulations dangereuses ?

Trois questions à poser avant de conclure :

- Ce résultat s'applique-t-il à mon secteur et à mes données réelles ?
- Qui a validé la qualité de ces exemples, et selon quels critères ?
- Ce niveau de performance est-il suffisant pour mon usage, ou faut-il encore une supervision humaine ?

→ Pour aller plus loin : [docs/how-to-read-results.md](docs/how-to-read-results.md)

## Limites et points d'attention

- Les résultats dépendent fortement du contexte : une IA peut réussir une tâche dans un domaine et échouer dans un autre très similaire.
- Les livrables n'ont pas été validés par des professionnels du secteur concerné — il s'agit d'un exercice éducatif, pas d'une certification.
- L'évaluation repose sur 10 tâches seulement : trop peu pour généraliser à un secteur entier.
- Les performances des IA évoluent vite : ce qui est vrai aujourd'hui peut être dépassé dans quelques mois.
- Aucune donnée réelle ou sensible n'a été utilisée : les résultats ne reflètent pas les contraintes d'un environnement de production.

→ Pour aller plus loin : [docs/limits.md](docs/limits.md)

## Origine / attribution

Inspiré d'un projet existant, adapté ici à des fins éducatives.

Ce dépôt est une adaptation du projet original **amaarora/GDPVal** :
👉 [https://github.com/amaarora/GDPVal](https://github.com/amaarora/GDPVal)

Le billet de blog d'origine, qui explique le contexte et la démarche, est disponible ici :
👉 [https://amaarora.github.io/posts/2025-12-15-gdpval-review.html](https://amaarora.github.io/posts/2025-12-15-gdpval-review.html)

## Statut

- Éducatif / expérimental
- Contributions bienvenues

---

> **Proposition de description (About du dépôt)** : *Repère éducatif : observe si une IA peut accomplir des tâches professionnelles réelles, de bout en bout. Inspiré de amaarora/GDPVal.*
