# Critters Simulation

This Python program simulates a world of different critters interacting in a 2D grid environment. The simulation includes various types of critters (Bears, Cheetahs, Lions, and Toreros) that can move, eat, fight, and mate.

## Features

- Graphical user interface using Tkinter
- Multiple critter types with unique behaviors
- Food spawning and consumption
- Critter battles and mating
- Turn-based simulation with adjustable speed
- Real-time statistics display

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## How to Run

1. Ensure you have Python installed on your system.
2. Save the `critters.py` file to your local machine.
3. Open a terminal or command prompt.
4. Navigate to the directory containing `critters.py`.
5. Run the following command:

   ```
   python critters.py
   ```

## Controls

- **Start**: Begins the automatic simulation.
- **Stop**: Pauses the automatic simulation.
- **Tick**: Advances the simulation by one turn.
- **Turn Speed**: Adjusts the speed of the automatic simulation.

## Critter Types

1. **Bear**: Alternates between moving north and west. Always eats when possible.
2. **Cheetah**: Moves in a random direction for three turns, then chooses a new random direction. Eats based on hunger level.
3. **Lion**: Moves in a specific pattern (5 south, 5 west, 5 north, 5 east). Eats after fighting.
4. **Torero**: Moves randomly or towards the east. Has random eating and fighting behavior.

## Simulation Rules

- Critters can move, eat, fight, and mate.
- Food spawns randomly in the world.
- Critters fall asleep after eating too much.
- Different critter types fight when they encounter each other.
- Same critter types mate when they encounter each other.

## Customization

You can modify the simulation parameters at the bottom of the `critters.py` file:

```python
if name == "main":
    simulate(60, 50, 25)
```

Adjust these values to change the world size and the number of each critter type.

## Acknowledgements

Dr. Sat Garcia wrote the starter code in `critters.py` and I implemented the Bear, Cheetah, Lion, and Torrero classes.
