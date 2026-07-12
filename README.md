# Embergate Arena

Embergate Arena is an original real-time lane strategy game built with a deterministic fixed-timestep simulation.

## Features
* **Real-time Strategy:** Battle for control over three bridges in a fast-paced environment.
* **Deterministic Simulation:** Uses a 30 Hz fixed-timestep sim, ensuring consistent gameplay and replayability.
* **Data-Driven Balance:** Unit and card stats (cost, HP, damage, range) are defined in a central JSON balance table for easy rebalancing.
* **Progression System:** Earn trophies, gold, and XP to level up your collection.
* **Achievements & Leaderboards:** Track your progress against other commanders.

## Technical Details
* **Engine:** Pure HTML5 Canvas & JavaScript.
* **Simulation:** Deterministic, command-driven architecture with a `NetAdapter` interface for potential multiplayer synchronization.
* **AI:** Included `LocalLink` bot provides a challenging opponent by using the same command pipeline as a human player.
* **Storage:** Persistent progression data stored via browser-based key-value storage.

## How to Play
1. **Battle:** Deploy your units in your half of the arena (or in captured enemy territory) to attack opposing towers.
2. **Strategy:** Manage your energy efficiently and play the right cards at the right time.
3. **Deck Builder:** Customize your deck of 8 cards and upgrade them to higher levels using gold earned from battles.

## Contributing
* The game is entirely self-contained within the provided HTML file.
* To balance the game, modify the `DATA` JSON object directly in the script section.
* All assets (visuals, unit shapes) are rendered procedurally via Canvas, allowing for easy visual modifications.

---
*Created as an original real-time lane strategy project.*
