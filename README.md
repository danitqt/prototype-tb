# TraceMe — Comprendre tes traces numériques

Prototype d'outil pédagogique numérique conçu dans le cadre d'un Travail de Bachelor à la Haute école de gestion de Genève (filière Informatique de gestion).

**Sujet** : Sensibilisation aux traces numériques et à l'identité numérique chez les élèves du Cycle d'orientation.
**Auteur** : Daniel Alves
**Directrice** : Mme Nathalie Courtine

---

## Présentation

TraceMe est une application web interactive qui simule une année dans la vie numérique d'un adolescent, de septembre à août. À chaque mois correspond une situation typique de la vie en ligne (création d'un compte, vidéo virale, message d'un inconnu, candidature à un stage…). L'élève fait des choix et en observe immédiatement les conséquences sur un smartphone simulé, plutôt que d'écouter une liste de recommandations.

L'objectif n'est pas de faire peur ni de culpabiliser, mais de **rendre visibles des mécanismes habituellement invisibles** : les traces produites passivement, le profilage algorithmique, la persistance des publications et leur diffusion.

## Fondements

Le prototype s'appuie sur deux cadres théoriques :

- le **modèle tripartite de l'identité numérique** de Fanny Georges (identité déclarative, agissante et calculée) ;
- les **quatre propriétés des traces numériques** décrites par Danah Boyd (persistance, réplicabilité, diffusabilité, recherchabilité).

## Comment l'utiliser

Aucune installation ni inscription n'est requise.

- **En ligne** : ouvrir l'adresse de démonstration (voir ci-dessous).
- **En local** : télécharger le fichier `index.html` et l'ouvrir par un double-clic dans n'importe quel navigateur récent.

Le parcours complet dure environ 15 minutes, ce qui correspond à une partie de séance de cours.

## Démonstration en ligne

https://danitqt.github.io/prototype-tb/

## Fonctionnalités principales

- Parcours narratif de douze chapitres correspondant aux douze mois d'une année scolaire.
- Smartphone simulé qui réagit visuellement à chaque choix (Instagram, WhatsApp, TikTok, Snapchat, recherche Google…), entièrement recréé en HTML et CSS.
- Quatre indicateurs suivis en temps réel : vie privée, e-réputation, bien-être et profil algorithmique.
- Révélation finale simulant la recherche d'un recruteur sur le nom de l'élève.
- Mode enseignant avec tableau de bord de résultats agrégés (données fictives à titre de démonstration).

## Aspects techniques

- Application web monopage en **HTML, CSS et JavaScript natif**, regroupée dans un fichier unique sans dépendance externe.
- **Aucune donnée personnelle n'est collectée ni transmise** : les choix restent dans le navigateur le temps de la session, conformément à la nouvelle loi suisse sur la protection des données (nLPD).
- Les interfaces des applications connues sont recréées en HTML et CSS, sans capture d'écran des applications originales, afin d'éviter tout problème de droits d'auteur.

## Confidentialité

Ce prototype ne contient aucun traceur et n'envoie aucune donnée à un serveur. Il fonctionne entièrement côté client.

## Note sur les contenus sensibles

Certaines situations abordent des thèmes délicats (cyberharcèlement, partage non consenti d'images). Elles sont traitées avec mesure et orientent systématiquement vers des ressources adaptées à l'âge concerné, comme le dialogue avec un adulte de confiance ou la ligne **147 de Pro Juventute**. Tout usage en classe devrait être accompagné par un adulte.

---

*Ce dépôt accompagne un Travail de Bachelor académique. Le prototype constitue une preuve de concept et non un produit fini destiné à un déploiement commercial.*
