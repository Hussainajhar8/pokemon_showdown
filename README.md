# Pokémon Showdown

Welcome to Pokémon Showdown! This is a simple console-based game where players select their Pokémon and battle against each other until one emerges victorious. The game retrieves Pokémon data from the PokeAPI, allowing players to choose from a wide range of Pokémon.

## How to Play

1. **Installation**: Ensure you have Python installed on your system.

2. **Setup**: Run the Python script `pokemon_showdown.py`.

3. **Game Start**: Upon starting the game, you'll be prompted to select your Pokémon. Enter the name of your Pokémon when prompted.

4. **Battle Commencement**: Once both players have selected their Pokémon, the battle begins. Each player takes turns attacking and selecting moves.

5. **Attacking**: Players choose their moves from a selection of available moves. Damage dealt is random, with a slight advantage given to the second player's attacks.

6. **Victory**: The battle continues until one player's Pokémon's health drops to zero. The victorious player is declared the winner.

## Dependencies

- This game relies on the `requests` and `random` Python libraries for retrieving Pokémon data and simulating battles, respectively.

## Attribution

- Pokémon data is fetched from the [PokeAPI](https://pokeapi.co/).
