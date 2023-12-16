# 486mlproject

## Purpose:

Classifying the type of a Pokemon based on its image or base stats.

## Sources:

* https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types (Kaggle dataset of Pokemon images)

* https://pokeapi.co/docs/v2#pokemon (website with all kinds of data involving Pokemon)

* https://medium.com/m2mtechconnect/classifying-pok%C3%A9mon-images-with-machine-learning-79b9bc07c080 (a resource for some EDA that was done on the Kaggle dataset)

## Files and Directories:

* images/images: directory of Pokemon images.

* pokemon.csv: CSV that comes from the Kaggle dataset.  It contains the Pokemon name and type(s).

* pokemon_type_and_base_stats.csv: scraped directly from the PokeAPI website that contains the type and base stats of each Pokemon.

* pokemon_type_and_base_stats_ratios.csv: feature engineered dataset that has the type and ratios of base stats of each Pokemon, where each base stat is divided by "speed" except for itself.
