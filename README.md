#dashcode

Application de gestion d'options vanilles

Télécharger le dossier puis lancer le script Page.py (avec un environnement python3 obligatoire).

L'outil se nourrit d'un fichier CSV comprenant toutes les actions possibles du marché français et mondial. L'utilisateur choisit les actions à mettre dans son portefeuille. Les caractéristiques principales sont ensuite importées du CSV automatiquement mais celles nécessaires au pricing d'une option vanille doivent être remplies par l'utilisateur (comme la maturité et le volume).
Le prix de l'option (call ou put) est calculé automatiquement via Black&Scholes et un simulateur permet à l'utilisateur de voir quelle variation peut mettre en danger son portefeuille. 
