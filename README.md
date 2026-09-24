# ADH

**Le logiciel que votre métier attend.**

ADH construit des logiciels métier sur mesure, des chaînes de données et des
automatisations. Depuis Antananarivo, entièrement à distance. Le fuseau couvre la journée
de bureau européenne, donc les échanges se font en direct.

Trois portes d'entrée, à prix ferme fixé avant de commencer :

- **Application métier**, quand le logiciel du marché ne suffit plus et que les tableurs
  ont atteint leur limite. 4 000 à 8 000 EUR, 3 à 4 semaines.
- **Données et documents**, une chaîne qui lit, contrôle et écrit sans intervention, et
  qui signale les cas douteux au lieu de les deviner. 2 500 à 5 000 EUR, 2 à 3 semaines.
- **Reprise de code existant**, un code que plus personne n'ose toucher, remis sous tests
  et rendu modifiable. 1 500 à 3 000 EUR, 1 à 2 semaines.

Les dépôts ci-dessous sont publics pour une raison simple : vous pouvez juger le travail
avant de nous parler, et le faire relire par votre équipe technique.

---

## Data, prévision et pipelines

| Dépôt | Ce qu'il fait |
| --- | --- |
| [stocksense](https://github.com/adh-studio/stocksense) | Prévision probabiliste de la demande à 14 jours sur 40 références et 6 points de distribution, convertie en politique de réapprovisionnement chiffrée. SQL, scikit-learn, PyTorch. [Démo en ligne](https://adh-studio.github.io/stocksense/). |
| [prospection-data-pipeline](https://github.com/adh-studio/prospection-data-pipeline) | Pipeline ETL en sept étapes sur 32 912 entreprises du registre national : nettoyage, scoring, découverte de contacts, exports. Gratuit par défaut, les sources payantes en option. |

## Agents IA et extraction de documents

| Dépôt | Ce qu'il fait |
| --- | --- |
| [llm-invoice-extractor](https://github.com/adh-studio/llm-invoice-extractor) | Extraction de factures par modèle de langage, avec une sortie classée exploitable, à relire ou inutilisable. Quatre contrôles métier décident du classement, pas le modèle. |
| [bank-statement-normalizer](https://github.com/adh-studio/bank-statement-normalizer) | CSV de toutes formes, OFX 1.x et 2.x, CAMT.053 ISO 20022 ramenés à une table unique, dédoublonnée, avec rapport des rejets. |
| [fec-validator](https://github.com/adh-studio/fec-validator) | Contrôle un Fichier des Écritures Comptables avant sa remise : 18 colonnes imposées, 26 règles, rapport console ou JSON. |

## Automatisation

| Dépôt | Ce qu'il fait |
| --- | --- |
| [n8n-automation-workflows](https://github.com/adh-studio/n8n-automation-workflows) | Workflows exploités en production : accueil de newsletter, capture de prospects, synchronisation CRM. Nœuds idempotents, branches d'erreur explicites, aucune défaillance silencieuse. |

## Applications métier

| Dépôt | Ce qu'il fait |
| --- | --- |
| [time-tracking-platform](https://github.com/adh-studio/time-tracking-platform) | Suivi du temps sur une centaine de postes Mac et Windows, y compris hors ligne. Agent Electron, tableau de bord temps réel, Node.js, Prisma, Redis. |
| [hr-management-app](https://github.com/adh-studio/hr-management-app) | Congés, présence, calendrier d'équipe, variables de paie, double authentification. React, Tailwind, Node.js. |
| [marketing-cost-tracker](https://github.com/adh-studio/marketing-cost-tracker) | Hub interne de suivi des dépenses marketing, connexion par code PIN, assistant intégré. |
| [mileage-allowance-app](https://github.com/adh-studio/mileage-allowance-app) | Moteur du barème kilométrique fiscal français : puissance fiscale, tranches de distance, calcul et export. Next.js, Prisma. |

## Code hérité, reprise et audit

| Dépôt | Ce qu'il fait |
| --- | --- |
| [csharp-legacy-audit](https://github.com/adh-studio/csharp-legacy-audit) | Analyseur statique C# écrit à la main : 16 règles, et une sortie qui est un plan de refactorisation priorisé plutôt qu'une liste d'avertissements. |
| [angularjs-portail-client](https://github.com/adh-studio/angularjs-portail-client) | Portail client en AngularJS 1.8.3, couvert par 160 tests Karma avant toute modification. ui-router, interopérabilité jQuery. |
| [mvc5-dossiers-cabinet](https://github.com/adh-studio/mvc5-dossiers-cabinet) | Back-office de suivi de dossiers en ASP.NET MVC 5 sur .NET Framework 4.8, Razor, Entity Framework 6. |

---

## Ce que nous faisons, et ce que nous ne faisons pas

Nous développons en **TypeScript, JavaScript, Python, C# et .NET**, côté web comme côté
bureau, et nous traitons des données de la requête SQL au modèle entraîné. Le langage
suit le projet, pas l'inverse.

Pas de mobile natif, pas de système embarqué, pas de jeu vidéo. Quand un sujet sort de ce
que nous savons tenir, nous le disons avant de commencer plutôt qu'au milieu.

## Comment nous travaillons

1. Un appel de trente minutes sur ce qui bloque aujourd'hui.
2. Un cadrage écrit : ce qui est fait, ce qui ne l'est pas, le prix ferme, la date.
3. La construction, avec un point d'avancement par semaine.
4. La remise : le code, la documentation en français et une séance de prise en main.

## Nous joindre

[LinkedIn](https://www.linkedin.com/in/adh-studio) pour en parler.
L'offre et les prix : [adh-studio.github.io](https://adh-studio.github.io/).
