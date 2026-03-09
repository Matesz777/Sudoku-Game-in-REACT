# Sudoku Game in React

A modern Sudoku game built with **React** and **Vite**, featuring puzzle generation, board validation, reset controls, and an integrated backtracking solver.

## Overview

This project is a browser-based Sudoku application designed to let users play, validate, reset, and automatically solve Sudoku puzzles in a clean React interface.

The app fetches a fresh puzzle from an external Sudoku API, renders a 9×9 interactive board, and allows the player to:

- enter values manually,
- check whether the puzzle is solved correctly,
- reset the board to the original puzzle state,
- generate a new puzzle,
- solve the puzzle automatically using a backtracking algorithm.

## Features

- **9×9 interactive Sudoku board**
- **Fetch new puzzle** from an online Sudoku API
- **Manual input** for editable cells
- **Reset** to the original puzzle state
- **Check solution** against the fetched answer
- **Auto-solve** using a backtracking algorithm
- **Selected-cell highlighting**
- **Completion feedback** for correct and incorrect solutions

## Tech Stack

- **React 19**
- **Vite 7**
- **JavaScript (ES modules)**
- **classnames**
- **ESLint**

## Project Structure

```text
Sudoku-Game-in-REACT/
├── src/                  # experimental/root React app
├── sudoku/               # main Sudoku application
│   ├── src/
│   │   ├── algorithm/
│   │   │   └── backtracking.js
│   │   ├── components/
│   │   │   ├── Board.jsx
│   │   │   ├── Controls.jsx
│   │   │   └── fetch.js
│   │   ├── App.jsx
│   │   ├── App.css
│   │   ├── index.css
│   │   └── main.jsx
│   ├── package.json
│   └── package-lock.json
├── package.json          # separate root app config
└── package-lock.json
