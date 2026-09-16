
# Introduction (Engineering des prompts)

## Ce que vous apprendrez dans ce module 

### Comprendre les modèles de langage
Découvrez ce que sont les LLM, leur fonctionnement interne et les principes qui
les gouvernent.

### Capacités et limites des LLM
Identifiez ce que ces modèles peuvent faire efficacement et leurs limitations
actuelles.

### Principes du prompt engineering
Apprenez les bases pour formuler des requêtes claires et obtenir des résultats
pertinents.

### Expérimentation pratique
Mettez en pratique vos connaissances avec des exercices guidés et des
expérimentations directes.



## Introduction de 'AI'

### History

1950 - Alan Turing "Turing test" le but est d'évaluer si une machine peut faire preuve d'une intelligence équivalente à celle de l'être humain

1956 - La conférence de Dartmouth : l'expression « intelligence artificielle » est officiellement créée par John McCarthy lors de cet événement fondateur

1957 - "Perceptron" Frank Rosenblatt crée le premier réseau de neurones artificiels simple

1985 - Boltzmann machines ont été inventées par Geoffrey Hinton et Terry Sejnowski.

1986 - Geoffrey Hinton, David Rumelhart et Ronald Williams ont popularisé l'algorithme de "backpropagation"

1997 - Sepp Hochreiter et Jürgen Schmidhuber inventé Long Short-Term Memory (LSTM)

1998- Yann LeCun, Léon Bottou, Yoshua Bengio et Patrick Haffner ont publié un article fondateur intitulé « Gradient-Based Learning Applied to Document Recognition ».

2017 - « Attention Is All You Need » est un article de recherche sur l'apprentissage automatique rédigé par huit scientifiques et ingénieurs travaillant chez Google. Cet article a introduit une nouvelle architecture d'apprentissage profond appelée « Transformer », fondée sur le mécanisme d'attention proposé en 2014 par Bahdanau et al.

2018 - openai créer GPT-1 (Generative Pre-trained Transformer)

2019 - openai créer GPT-2

2020 - openai créer GPT-3

## Les Types de machine learning

### Supervised Learning

- Définition : Apprentissage à partir de données étiquetées, où le modèle reçoit à la fois l'entrée et la sortie correcte (à l'instar d'un corrigé).

- Fonctionnement : L'algorithme étudie des paires d'exemples pour associer les entrées aux sorties et prédire les réponses pour de nouvelles données.

- Applications courantes : Filtrage des e-mails indésirables (spam), reconnaissance d'images et prévision du prix des logements.

### Unsupervised Learning

- Définition : Découverte de structures ou de modèles cachés au sein de données non étiquetées, sans intervention humaine ni réponses prédéfinies.

- Fonctionnement : L'algorithme trie les données brutes pour regrouper des éléments similaires ou détecter des anomalies de manière autonome.

- Applications courantes : Segmentation de la clientèle, analyse du panier d'achat et détection d'anomalies.

### Reinforcement Learning

- Définition : Apprentissage d'une prise de décision optimale par essais et erreurs, grâce à l'interaction avec un environnement dynamique.

- Fonctionnement : Un agent d'IA effectue des actions et reçoit un retour sous forme de récompenses ou de pénalités, dans le but de maximiser la récompense cumulée au fil du temps.

- Applications courantes : IA jouant à des jeux (comme les échecs ou le jeu de go), robotique et véhicules autonomes.

## Shallow Learning vs Deep Learning

L'apprentissage superficiel (Shallow Learning) utilise des modèles simples à une ou deux couches qui nécessitent une intervention humaine pour trier les données, tandis que le Deep Learning utilise des réseaux de neurones profonds à plusieurs couches pour analyser les informations de manière autonome.

### ML vs DL


## L'IA générative

L'IA générative ne se contente pas de classer ou de prédire : elle crée du contenu nouveau à
partir d'une consigne (prompt).

Elle peut écrire un texte, générer une image, produire du code ou composer de la musique, en
s9appuyant sur d9énormes volumes de données qu9elle a appris à imiter.

C'est ce qui permet à des outils comme ChatGPT ou DALL·E de produire des résultats
originaux à partir d'une simple demande en langage naturel.

## Prompt Engineering

Le prompt engineering est l'art de créer des instructions claires pour
obtenir de bonnes réponses d'une IA générative.

C'est un mélange de connaissances techniques et de compétences en
communication pour tirer le meilleur des systèmes d'IA.

Un bon prompt guide l'IA vers la réponse que vous cherchez, en évitant les
confusions et en améliorant la précision.