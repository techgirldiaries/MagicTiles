# 2048 JavaScript Game

## Introduction

This project is a browser-based implementation of the classic 2048 puzzle game, built using Vanilla JavaScript, HTML and CSS. It focuses on translating well-defined game mechanics into clean, readable front-end logic without relying on frameworks or external libraries.

The implementation demonstrates how core JavaScript concepts can be applied to manage state, handle user input and update the DOM dynamically in response to game events.

## Game Rules

- 2048 is played on a 4×4 grid using the arrow keys.

- Tiles slide in the selected direction until blocked by another tile or the grid edge

- After each move, a new tile appears in a random empty position

- Tiles with the same value merge when they collide, forming a tile with their combined value

- A tile can merge only once per move

- The game ends when no valid moves remain

## Technical Focus

This project emphasises:

- DOM manipulation and event handling

- Game state management using arrays

- Game logic and collision handling

- Random tile generation and grid updates

- Clean separation of logic, structure, and styling

## JavaScript Concepts & Methods Used

- querySelector()

- getElementById()

- createElement()

- appendChild()

- addEventListener() / removeEventListener()

- setTimeout() / setInterval() / clearInterval()

- Math.floor() / Math.random()

- Array methods including push(), filter(), concat(), fill()

- parseInt()

- Keyboard input handling

## Development Environment

[VS Code](https://code.visualstudio.com/)

## Acknowledgements

Inspired by learning resources and tutorials created by [Ania Kubów](https://github.com/kubowania), whose educational content helped shape the approach taken in this implementation.

## License

This project is licensed under the PolyForm Noncommercial License.
Commercial use is not permitted.

Copyright (c) 2025 Oluwakemi T. Obadeyi
