# NBA League Manager

A Java console program that models an NBA league as conferences, teams and players, and prints the whole structure.

> Learning project — written in 2025 while learning object-oriented programming in Java.

## Overview

The program builds a small league in memory: two conferences, six teams and thirty players. Each player has a name, a number and a height, and belongs to one of four position classes that extend a common `Jugador` class. Running it prints the league conference by conference.

The project practises inheritance, composition (a league holds conferences, which hold teams, which hold players) and collections. The data is written directly in `Main.java`. The output and the code comments are in Spanish.

## Getting started

Requires JDK 8 or later.

```bash
git clone https://github.com/AketzaBarajas/nba-league-manager.git
cd nba-league-manager
javac -encoding UTF-8 -d out src/*.java
java -cp out Main
```

## License

[MIT](LICENSE)
