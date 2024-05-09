# Conway's Game of Life Simulation
**Maker:** Kavya Chowti & Shamiya Lin
**University of Texas at Austin Machine Learning and Data Science Club Long Competition Placement:** 3rd Place

## Agents

### Agent 1
**Tactics:**
- **Objective:** Attack enemy agents while avoiding overpopulation.
- **Observation:** Observes adjacent cells for enemy positions and empty spaces.
- **Action:** Prioritizes attacking nearby enemies or moving to less populated areas.
- **Strategy:** Utilizes a toroidal grid approach for map navigation.
- **Randomness:** Incorporates randomness for enemy targeting and movement.

### Agent 2
**Tactics:**
- **Objective:** Evaluate states and select actions to maximize score.
- **State Evaluation:** Scores states to assess action benefits.
- **Action Selection:** Generates legal actions and selects the highest scoring action.
- **Exploration:** Implements exploration during training for optimal action selection.

### Agent 3
**Tactics:**
- **Objective:** Learn optimal policies through Q-learning.
- **State Representation:** Converts states to suitable representations for learning.
- **Action Selection:** Utilizes Q-learning policy for action selection.
- **Exploration-Exploitation:** Balances exploration and exploitation using an epsilon-greedy strategy.


### Conway's Game of Life

- Implements Conway's Game of Life rules for simulation.
- Grid-based environment where agents compete for survival.
- Agents evolve according to cellular automaton rules.
- Customizable parameters such as board size and maximum rounds.
