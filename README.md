# Trading-Model

Notebooks d'exploration pour la prédiction de prix sur le marché Forex avec [Prophet](https://facebook.github.io/prophet/), à partir de données récupérées en direct via MetaTrader 5.

## Contenu

- `USDJPYm.ipynb` — modèle de prédiction sur la paire USD/JPY
- `XAUUSDm.ipynb` — modèle de prédiction sur l'or (XAU/USD)

Chaque notebook se connecte au terminal MetaTrader 5 en local (`MetaTrader5` Python package), récupère l'historique de prix, puis entraîne un modèle Prophet pour projeter la tendance à court terme.

## Prérequis

- Un terminal MetaTrader 5 installé et connecté à un compte (démo ou réel)
- `pip install MetaTrader5 pandas numpy mplfinance prophet`

## Statut

Travail exploratoire — ces notebooks servent de base de recherche, pas de système de trading prêt à l'emploi.
