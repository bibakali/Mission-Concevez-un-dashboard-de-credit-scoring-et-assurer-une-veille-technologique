# Mission-Concevez-un-dashboard-de-credit-scoring-et-assurer-une-veille-technologique
Certification OpenClassrooms - Parcours data scientist - Mission n°8 - Concevez un dashboard de credit scoring et assurer une veille technologique


## Missions 
### Concevoir un dashboard de credit de scoring
Je suis  Data Scientist au sein d'une société financière nommée Prêt à dépenser, qui propose des crédits à la consommation pour des personnes ayant peu ou pas du tout d'historique de prêt. 
Vous venez de mettre en œuvre un outil de “scoring crédit” pour calculer la probabilité qu’un client rembourse son crédit, et classifier la demande en crédit accordé ou refusé. 
Les chargés de relation client ont fait remonter le fait que les clients sont de plus en plus demandeurs de transparence vis-à-vis des décisions d’octroi de crédit. 
Prêt à dépenser décide donc de développer un dashboard interactif pour que les chargés de relation client puissent expliquer de façon la plus transparente possible les décisions d’octroi de crédit, lors de rendez-vous avec eux. Cette volonté de transparence va tout à fait dans le sens des valeurs que l’entreprise veut incarner.
### Assurer une veille technologique sur les traitements de textes : NLP 
Réaliser un état de l’art sur une technique récente de modélisation de données texte ou de données image, l’analyser, la tester et la comparer à une approche plus classique que j'ai déja réalisée précédemment ?
L’état de l’art devra concerner une technique datant de moins de 5 ans, présentée dans un article.
La technique doit être référencée sur des sites de recherche (Arxiv), des sites connus (par exemple fastml, machine learning mastery, kdnuggets, import AI, MIT tech review, MIT news ML) ou des newsletters de qualité comme data elixir et data science weekly.
Tu réaliseras et nous présenteras une preuve de concept qui met en oeuvre cette nouvelle technique avec les données texte ou image que tu as déjà exploitées précédemment.
Tu nous expliqueras rapidement les concepts et techniques dans une note méthodologique (modèle en pièce-jointe) et lors d’une présentation.

## Source 
[Les données](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Implémenter+un+modèle+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip)

## Axes d'orientations 
### Dashboard : 
- Commencez par des maquettes simplifiées pour valider l'approche avec les utilisateurs.
- Pour la réalisation technique du Dashboard vous pouvez vous appuyer sur les librairies Dash ou Bokeh, ainsi qu’avec Streamlit.
- Assurez-vous que votre prototype initial du dashboard comprend des fonctionnalités clés :
  - visualisation du score de crédit (jauge colorée) et la contribution des features qui ont amené le modèle à prédire le score (feature importance locale et sa comparaison avec la feature importance globale) ;
  - visualisation des caractéristiques clients et comment ils se situent par rapport aux autres clients sous forme de graphiques (possibilité de choisir feature par feature) ;
  - graphique d’analyse bi-variée entre deux features sélectionnées ;
  - autres graphiques pertinents pour la présentation des données client ;
- Intégration d'une API pour récupérer le score du client ;
- Interface pour la modification des informations client via l'API.

### NLP : 
- Choisissez rapidement les étapes (pre-processing, postprocessing, feature engineering etc.) et hypothèses qui resteront fixes pour le POC. L’idée n’est pas de refaire la pipeline de ML de bout en bout, mais de rapidement expérimenter.
- Une piste à explorer parmi d’autres est le Transformer et ses variantes. C’est une architecture de réseaux de neurones qui constitue le fondement de toutes les méthodes de NLP et de vision modernes comme les LLMs. 
- Soyez vigilant au temps de calcul de certaines méthodes état de l’art, surtout si vous envisagez un ré-entraînement d’architectures lourdes. Vous pouvez envisager de réduire la taille du jeu de données d'entraînement par exemple.

## Compétences 
- Mettre en place un dashboard intéractif avec streamlit
- Deployer et tester le dashboard sur le web 
- Mettre en place une technique récente d'utilisation de Traitements de texte NLP
- Pour cette veille technologique, il sera question de traitement de langage naturel (NLP). Principalement: Le modèle T5, ou "Text-To-Text Transfer Transformer",  qui est une architecture de réseau neuronal développée par Google AI.
