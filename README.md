# 486mlproject

## Sources:

* https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types

* https://pokeapi.co/docs/v2#pokemon

* https://medium.com/m2mtechconnect/classifying-pok%C3%A9mon-images-with-machine-learning-79b9bc07c080 (a resource for some EDA that was done on the Kaggle dataset)

## Files:

* pokemon.csv: CSV that comes from the Kaggle dataset.  It contains the Pokemon name and type(s).

* pokemon_type_and_base_stats.csv: scraped directly from the PokeAPI website that contains the type and base stats of each Pokemon.

* pokemon_type_and_base_stats_combos.csv: feature engineered dataset that has the type and combinations of base stats of each Pokemon, including "attack and special attack," "defense and special defense," "attack and speed," and "special attack and speed."

* pokemon_type_and_base_stats_ratios.csv: feature engineered dataset that has the type and ratios of base stats of each Pokemon, where each base stat is divided by "speed" except for itself.
