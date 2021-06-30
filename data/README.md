# Pokemon dataset

There is one dataset here: `pokemon.csv`

This dataset is downloaded from [Kaggle](https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420)


This file contains information about 890 pokemon (1028 including varieties). The information is sorted in different groups:

```
Pokedex Data:

pokedex_number: The entry number of the Pokemon in the National Pokedex
name: The English name of the Pokemon
german_name: The German name of the Pokemon
japanese_name: The Original Japanese name of the Pokemon
generation: The numbered generation which the Pokemon was first introduced
status: Denotes if the Pokemon is normal, sub legendary, legendary or mythical
species: The Categorie of the Pokemon
type_number: Number of types that the Pokemon has
type_1: The Primary Type of the Pokemon
type_2: The Secondary Type of the Pokemon if it has it
height_m: Height of the Pokemon in meters
weight_kg: The Weight of the Pokemon in kilograms
abilities_number: The number of abilities of the Pokemon
ability_?: Name of the Pokemon abilities
ability_hidden: Name of the hidden ability of the Pokemon if it has one
Base stats:

total_points: Total number of Base Points
hp: The Base HP of the Pokemon
attack: The Base Attack of the Pokemon
defense: The Base Defense of the Pokemon
sp_attack: The Base Special Attack of the Pokemon
sp_defense: The Base Special Defense of the Pokemon
speed: The Base Speed of the Pokemon
Training:

catch_rate: Catch Rate of the Pokemon
base_friendship: The Base Friendship of the Pokemon
base_experience: The Base experience of a wild Pokemon when caught
growth_rate: The Growth Rate of the Pokemon
Breeding:

egg_type_number: Number of groups where a Pokemon can hatch
egg_type_?: Names of the egg groups where a Pokemon can hatch
percentage_male: The percentage of the species that are male. Blank if the Pokemon is genderless.
egg_cycles: The number of cycles (255-257 steps) required to hatch an egg of the Pokemon
Type defenses:

against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type
```