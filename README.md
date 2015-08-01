# Pokemon dual type analysis

## Overview

In the world of Pokémon there are 18 types that are properties of the Pokémon and their moves. A Pokémon may have one or two types (dual type), meaning that there are 324 posible combinations, 18 single type Pokémon and 306 dual types Pokémon. However in the games, there are no differences between the order of the types in a dual type Pokémon, in other words, a Flying/Dragon Pokémon is treated in the same way a Dragon/Flying Pokémon is treated.

In this work we will take a look at dual type Pokémon. The analysis is mostly an exploratory data analysis where we will study topics such as most frequent secondary type by primary type, the most common secondary types by region and in the last part, we will introduce a prediction model to see if there is any relation between dual types Pokémon and their region of origin.

Unlike the games, we will consider the order of the types of a dual type Pokémon using the way it is documented in the Pokedex. For example, we will treat a Flying/Dragon Pokémon such as Noivern and Dragon/Flying Pokémon like Altaria as having two different types.

The Pokémon included in this study are the ones currently available in the National Pokedex, starting with Bulbasaur and ending with Zygarde; a total of 718 Pokémon. Also, Mega Pokémon and alternate forms of Pokémon like Rotom forms and the Therian forms are not included.

This analysis was done using R.


## Project

This repository contains the Markdown file that holds the analysis plus the R code, an R script with just the code, the original dataset used (in txt) and the HTML version of the report.

The analysis can be found [here](http://juandes.github.io/PokemonDualTypeAnalysis/docs/dual_types_analysis).
