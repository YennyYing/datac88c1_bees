# Ants vs. SomeBees (Tower Defense Simulation)

## Description
A Python-based tower-defense simulation inspired by Plants vs. Zombies. The project implements a full object-oriented game engine where different ant types defend their colony from invading bees. Players can explore unique ant abilities, container mechanics, ranged attacks, status effects, and simulated turns within a multi-tunnel layout.  

**Live Game:** 

![Ants animation](https://raw.githubusercontent.com/YennyYing/datac88c1_bees/main/ants.gif)

## Author
Yuan Ying  

## Date
05/2025  

---

## How It's Made:

**Tech used:** Python, Object-Oriented Programming, Inheritance, Simulation Modeling

This project was built as a turn-based simulation game in Python. The implementation centers around a structured class hierarchy (`Insect`, `Ant`, `Bee`, `Place`, etc.) that models combat interactions, movement, and turn-by-turn state updates.

I implemented multiple ant subclasses featuring specialized mechanics—ranged attackers, explosive ants, container ants, aquatic ants, and a final Queen Ant with permanent buff logic. The simulation loop handles bee waves, ant actions, and environmental constraints such as water tiles.

This project highlights my ability to design clean, modular systems, extend classes through inheritance, and build a fully functional simulation engine from scratch.

## Features
- Full turn-based simulation with GUI and CLI modes
- Multiple ant types with unique attack styles and cooldowns
- Container ants that allow stacking abilities (BodyguardAnt, TankAnt)
- Special effects including slow, scare, and splash damage
- Support for aquatic tiles and underwater ants
- Queen Ant mechanics with permanent damage buffs
- Predefined enemy waves and hive structure

---

## Packages
```markdown
The project uses only Python’s built-in libraries.  
Run the game with:
python3 ants.py
python3 ants_gui.py
