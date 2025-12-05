# Ants vs. SomeBees (Tower Defense Simulation)

## Description
A Python-based tower-defense simulation inspired by Plants vs. Zombies. The project implements a full object-oriented game engine where different ant types defend their colony from invading bees. Players can explore unique ant abilities, container mechanics, ranged attacks, status effects, and simulated turns within a multi-tunnel layout.  

**Live Game:**

![Ants animation](https://raw.githubusercontent.com/YennyYing/datac88c1_bees/refs/heads/main/ants.gif)

## Author
Yuan Ying  

## Date
05/2025  

---

## How It's Made:

**Tech used:** Python, Object-Oriented Programming, Inheritance, Simulation Modeling

This project was built as a **turn-based simulation game in Python**. The implementation centers around a structured class hierarchy (`Insect`, `Ant`, `Bee`, `Place`, etc.) that models combat interactions, movement, and turn-by-turn state updates.

I implemented multiple ant subclasses featuring specialized mechanics—ranged attackers, explosive ants, container ants, aquatic ants, and a final Queen Ant with permanent buff logic. The simulation loop handles bee waves, ant actions, and environmental constraints such as water tiles.

This project highlights my ability to design clean, modular systems, extend classes through inheritance, and build a fully functional simulation engine from scratch.

## Features
- **Turn-based battle system** with both GUI and command-line play
- **Diverse ant classes**, each with unique abilities, damage types, and cooldown mechanics
- **Stackable ant abilities** via container ants (e.g., BodyguardAnt, TankAnt)
- **Status effects** such as slowing, scaring enemies, and area-of-effect attacks
- **Aquatic mechanics** supporting underwater ants and water-specific behaviors
- **Queen Ant system** enabling global team buffs and long-term strategic advantages
- **Preconfigured enemy waves** and hive layouts to create structured, escalating difficulty

---
## Lessons Learned:
From this project, I learned how to design a multi-class system, manage interactions between many moving parts, and turn abstract rules into clean Python code. It strengthened my understanding of inheritance, state updates, debugging, and simulation design. Most importantly, it taught me how to structure a large Python project in a clear and maintainable way.
