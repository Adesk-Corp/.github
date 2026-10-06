<div align="center">

# ADESK CORP

### De l’information au sentiment. Du signal à la performance.

Nous construisons des outils pour comprendre les marchés financiers,<br>
transformer l’actualité en signaux mesurables et évaluer leur potentiel de PnL.

<br>

![Financial NLP](https://img.shields.io/badge/RESEARCH-Financial%20NLP-111827?style=for-the-badge&labelColor=0f766e)
![Quantitative Finance](https://img.shields.io/badge/FOCUS-Quantitative%20Finance-111827?style=for-the-badge&labelColor=0f766e)
![In development](https://img.shields.io/badge/STATUS-En%20développement-111827?style=for-the-badge&labelColor=0f766e)

</div>

---

## Notre ambition

Les marchés réagissent à des résultats d’entreprise, des annonces économiques, des événements géopolitiques et aux anticipations qu’ils suscitent. Notre ambition est de relier cette information aux actifs concernés, d’en mesurer la tonalité et d’étudier comment elle se traduit dans les prix.

**Adesk Corp réunit analyse de sentiment, ingénierie des données et recherche quantitative autour d’une même question : dans quelles conditions l’information peut-elle devenir un signal exploitable et produire une performance mesurable ?**

Nous voulons suivre toute la chaîne : retrouver la source d’un signal, comprendre sa construction, tester une règle de décision et mesurer les gains, les pertes et le risque associés.

## De l’actualité au PnL

Le parcours que nous cherchons à construire :

```mermaid
flowchart LR
    A[Actualités et données] --> B[Sentiment par actif]
    B --> C[Signaux quantitatifs]
    C --> D[Stratégies testables]
    D --> E[PnL et risque]

    style A fill:#0f172a,color:#f8fafc,stroke:#334155
    style B fill:#0f172a,color:#f8fafc,stroke:#334155
    style C fill:#0f766e,color:#ffffff,stroke:#14b8a6
    style D fill:#0f172a,color:#f8fafc,stroke:#334155
    style E fill:#0f766e,color:#ffffff,stroke:#14b8a6
```

| Étape | Ce que nous cherchons à faire |
| :--- | :--- |
| **01 · Capter** | Collecter l’actualité financière et les données de marché, conserver les sources et les horodatages, réduire les doublons. |
| **02 · Comprendre** | Identifier les actifs concernés et analyser la tonalité positive, négative ou neutre des informations avec des modèles de langage spécialisés. |
| **03 · Construire un signal** | Agréger les sentiments selon leur récence et leur contexte, puis confronter ces indicateurs aux mouvements de marché. |
| **04 · Tester une stratégie** | Définir des règles explicites d’entrée, de sortie et d’exposition, puis les évaluer sur des données historiques. |
| **05 · Mesurer** | Étudier le PnL net de coûts, les pertes maximales, la stabilité des résultats et leur sensibilité aux hypothèses. |

Un score de sentiment ne se convertit pas directement en euros. **Le PnL résulte des positions prises, de l’évolution des prix et des coûts d’exécution.** Notre objectif est de tester ce lien, en tenant compte du délai entre publication et décision, des frais et du glissement de prix.

## Ce que nous développons

### AlphaDesk · Le poste d’analyse

AlphaDesk rassemble notre travail sur la veille financière et l’exploration des marchés dans une interface commune.

- **Veille financière** : collecte RSS, traitement des actualités et synthèses.
- **Sentiment** : analyse de textes avec FinBERT et rattachement aux actifs suivis.
- **Marchés** : consultation des cours, graphiques et données de marché.
- **Options** : outils d’analyse des chaînes d’options et de la volatilité.

Ces briques évoluent au fil du développement ; leur intégration varie selon les branches de travail.

### Notre prochaine étape · Relier les signaux aux résultats

Nous souhaitons prolonger ce socle par une chaîne de recherche reproductible : constitution d’historiques horodatés, construction de signaux, backtests, validation hors échantillon et suivi du PnL simulé.

La mesure de performance constitue un **objectif de recherche**. Nous ne présentons pas à ce stade de rentabilité démontrée ni de moteur de trading automatisé validé.

## Notre méthode

**Des données traçables.** Chaque résultat doit pouvoir être relié à ses sources, à sa date et aux transformations appliquées.

**Des expériences reproductibles.** Les hypothèses, les versions des modèles et les règles des stratégies doivent être explicites pour permettre la comparaison des résultats.

**Une validation chronologique.** Nous voulons tester avec les seules informations disponibles au moment de la décision, puis vérifier les résultats sur des périodes non utilisées pour construire le signal.

**Une performance évaluée avec son risque.** Les gains doivent être lus avec les coûts, les pertes, l’exposition et les conditions de marché qui les ont produits.

## L’équipe

| | | |
| :--- | :--- | :--- |
| Quentin **Germain** | Matthis **Meunier** | Loup **Florentin** |
| Adil **Chobti** | Alexandre **Dousset** | Arthur **Lourenco** |

Nous croisons développement logiciel, traitement du langage et finance quantitative pour construire une chaîne d’analyse compréhensible, mesurable et améliorable.

---

<div align="center">

**Capter l’information. Comprendre le sentiment. Tester le signal. Mesurer le résultat.**

<sub>Adesk Corp · Financial intelligence & quantitative research</sub>

</div>
