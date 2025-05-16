# 🕹️ Pong Game in Pygame

> A simple yet fun implementation of the classic Pong game using Python and the Pygame library. Two players can compete in real-time using the keyboard!

---

## 📖 About

This project recreates the retro Pong arcade game using Pygame. Two players control paddles on each side of the screen to deflect a moving ball. The first player to score 10 points wins the match.


## ✨ Features

- 🧱 Classic Pong gameplay
- 🎮 Real-time two-player controls
- 🧠 Ball collision physics with paddle angle deflection
- 🔢 Dynamic score display
- 🏁 Win condition logic and reset

## 🛠️ Installation

Make sure you have **Python 3** installed, 
```bash
python --version
```

Then:
```bash
# Clone the repository
git clone https://github.com/yourusername/pong-pygame.git

# Navigate into the project directory
cd pong-pygame

# Install dependencies
pip install pygame
```

## 🚀 Usage

Run the game with:

```bash
python pong.py
```

### 🎮 Controls

* **Left Player:** `W` (up), `S` (down)
* **Right Player:** `↑` (up), `↓` (down)


## ⚙️ Configuration

You can modify game parameters directly in the `pong.py` file:

```python
WIDTH, HEIGHT = 700, 500
FPS = 60
WINNING_SCORE = 10
PADDLE_WIDTH, PADDLE_HEIGHT = 20, 100
BALL_RADIUS = 7
```

## 🧰 Technologies

* [Python](https://www.python.org/)
* [Pygame](https://www.pygame.org/)

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request