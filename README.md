
# 🧠 Memory Puzzle Game of Number Pairs (Python)

A simple yet engaging brain-training game built with **Python**, **Turtle Graphics**, and the **FreeGames** library.  
Players flip tiles to match identical number pairs — once all pairs are matched, a hidden image is revealed.

---

## 📜 Project Overview
The Memory Puzzle Game (also known as Concentration) is designed to:
- Improve memory and concentration.
- Provide an enjoyable interactive game experience.
- Demonstrate Python’s graphics capabilities with Turtle and FreeGames.

This project was implemented as part of the **Data Preprocessing and Data Visualization** skill-oriented course.

---

## 🚀 Features
- Interactive tile-flipping gameplay.
- Randomized tile layout using `shuffle()`.
- Reveal hidden background image after all matches.
- Clear and colorful tile design.
- Supports customization of tile colors and images.

---

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries/Modules:**
  - `turtle` – for drawing graphics and handling clicks.
  - `random` – for shuffling tiles.
  - `freegames` – for loading images and assets.

---

## 📂 Project Structure
```

.
├── memory\_game.py         # Main Python script
├── car.gif                # Background image
├── README.md              # Project documentation
├── screenshot1.png        # Closed tiles
├── screenshot2.png        # Partially revealed tiles
├── screenshot3.png        # Fully revealed image

````

---

## 📸 Screenshots
| Closed Tiles | Matching Tiles | Revealed Image |
|--------------|---------------|----------------|
| ![Closed](Screenshot1.png) | ![Matching](Screenshot2.png) | ![Revealed](Screenshot3.png) |

---

## ⚙️ Installation & Running the Game

### 1️⃣ Install Python
Download Python 3.x from [python.org](https://www.python.org/downloads/).

### 2️⃣ Install Dependencies
```bash
pip install freegames
````

### 3️⃣ Run the Game

```bash
python memory_game.py
```

---

## 🎮 How to Play

1. Click on a tile to reveal its number.
2. Click on another tile to try matching the number.
3. If both match, they remain revealed; otherwise, they are hidden again.
4. Continue until all tiles are matched and the background image is fully visible.

---

## 🧩 Code Highlights

* **Randomization:**

  ```python
  shuffle(tiles)  # Randomly rearranges tiles each game
  ```
* **Tile Drawing:**

  ```python
  def square(x, y):
      color('yellow', 'blue')
      ...
  ```
* **User Interaction:**

  ```python
  onscreenclick(tap)  # Registers mouse clicks
  ```

---

## 📚 References

1. [Python Turtle Graphics Documentation](https://docs.python.org/3/library/turtle.html)
2. [FreeGames Library](http://www.grantjenks.com/docs/freegames/)
3. Graham, Knuth, Patashnik – *Concrete Mathematics: A Foundation for Computer Science*

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify it.

---

👩‍💻 **Author:** Budati Lekha
📅 **Year:** 2022

```



