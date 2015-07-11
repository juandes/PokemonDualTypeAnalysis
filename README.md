# PokemonDualTypeAnalysis
In the world of Pokémon there are 18 types that are properties of the Pokémon and their moves. A Pok?mon may have one or two types (dual-type), meaning that there are 324 posible combinations, 18 single-type Pok?mon and 306 dual-types Pok?mon. However in the games, there are no differences between the order of the types in a dual-type Pok?mon, in other words, a Flying/Dragon Pok?mon is treated in the same way a Dragon/Flying Pok?mon is treated.

In this work we will take a look at dual-type Pok?mon. Unlike the games, we will consider the order of the types of a dual-type Pok?mon using the way it is documented in the Pokedex. For example, we will treat a Flying/Dragon Pok?mon such as Noivern and Dragon/Flying Pok?mon like Altaria as having two different types. 

The Pok?mon included in this study are the ones currently available in the National Pokedex, starting with Bulbasaur and ending with Zygarde; a total of 718 Pok?mon. Also, Mega Pok?mon and alternate forms of Pok?mon like Rotom forms, Therian forms are not included.


##About the project
This analysis was done in R. The .Rmd is a Markdown file done in R that contains the code of the analysis plus the documentation. To view the code, open the Rmd file in raw mode or execute it in R.

The file pokemontypes.txt is the dataset used in the analysis. It contains three columns, the number of the Pokemon and it types.

pokemontypesdf.RData contains the same data in an R data format.

The analysis is also available at this page: http://rpubs.com/juande/pokemon_dual_type_analysis
