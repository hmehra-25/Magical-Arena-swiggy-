# Magical Arena

## Description
A simulation of a magical arena where two players fight until one dies.

## How to Run
1. Install dependencies:
    ```bash
    npm install
    ```

2. Run the simulation:
    ```bash
    node src/main.js
    ```

3. Run the tests:
    ```bash
    npm test
    ```

## Project Structure
- `src/`: Contains the source code.
- `test/`: Contains the test cases.
- `README.md`: Instructions and documentation.

## Design Considerations
- Each player has attributes for health, strength, and attack.
- Players take turns attacking based on their health.
- Dice rolls determine the outcome of attacks and defenses.
- The game ends when one player's health reaches 0.
