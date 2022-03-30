# Data et campagnes marketing

## Contexte

Dans ce projet, nous allons aborder le Data Marketing pour AZG Banque et Assurances (entreprise fictive). L'enjeu est de prédire si un nouveau client sera sensible ou pas à une offre bancaire à partir des données de son CRM (Customer Relationship Management) dans le cadre d'une campagne de télémarketing. Ce type de campagne est une démarche qui peut être ressentie comme intrusif. Il est donc judicieux de bien segmenter les clients cibles pour à la fois ne pas renvoyer une image d'omniprésence, augmenter le lifetime customer et établir de bonnes relations.

![alt text](https://github.com/Lwmay/data_campagne_marketing/img/features.png?raw=true

## Méthodologie

À partir des données, nous analyserons la campagne précédente dans laquelle les commerciaux ont exécuté des appels téléphoniques à partir d'une liste de clients pour leur demander de souscrire à un DAT. Le résultat est un contact binaire échec ou réussite et ont été reportés dans le système de données CRM.

L'objectif à partir de ces données est de construire un modèle basé sur les données qui apprend une fonction sous-jacente inconnue qui mappe plusieurs variables d'entrée et qui va caractériser une cible de sortie étiquetée (type de vente de dépôt bancaire : "échec" ou "succès"). Ce modèle sera implémenté dans un programme de prédiction qui sera exécuté sur une liste de clients. L'entreprise aura ainsi une liste de clients ciblés avec leurs probabilités d'acceptation respectives.

![alt text](https://github.com/Lwmay/data_marketing/img/global_campagne.png?raw=true

Les données que nous analysons proviennent d'une étude sur le Marketing Data-Driven :
Source: : [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Sxystems, Elsevier, 62:22-31, June 2014.

## Compétences mises en oeuvre

- Réaliser une analyse prédictive
- Machine Learning
