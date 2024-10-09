# Tic-Tac-Toe Game

This is a command-line Tic-Tac-Toe game implemented in Python, where players can play the classic game on a 3x3 board. The first player to align three marks (either X's or O's) horizontally, vertically, or diagonally wins.

## Features

- Supports two players (X and O).
- Input validation to handle invalid moves.
- Display of the board after each turn.
- Russian error messages for invalid inputs.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sxdisbr/tic-tac-toe.git
   cd tic-tac-toe
   ```

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

```bash
python main.py
```

```css
tic-tac-toe/
│
├── gameparts/
│   ├── __init__.py
│   ├── exceptions.py
│   └── board.py
├── main.py
├── .gitignore
├── README.md
```

## Contributing

Feel free to submit issues or contribute by forking the repository and submitting a pull request.

## License

This project is licensed under the MIT License