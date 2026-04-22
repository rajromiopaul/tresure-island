# 🏝️ Treasure Island Game

Welcome to **Treasure Island**, a simple text-based adventure game written in Python.  
Your mission is to navigate through choices and find the hidden treasure… if you can survive! 💰

---

## 🎮 How the Game Works

The game is decision-based. At each stage, you’ll be prompted to make a choice.  
Your decisions will determine whether you win the treasure or meet a Game Over.

---

## 🧭 Game Flow

1. **Crossroad**
   - Choose `"left"` or `"right"`
   - Wrong choice leads to falling into a hole.

2. **Lake**
   - Choose `"wait"` or `"swim"`
   - Swimming results in being attacked by a trout.

3. **Island House**
   - Choose a door: `"red"`, `"yellow"`, or `"blue"`
   - Each door leads to a different outcome:
     - 🔴 Red → Fire (Game Over)
     - 🔵 Blue → Beasts (Game Over)
     - 🟡 Yellow → Treasure (You Win!)

---

## 🧑‍💻 How to Run

1. Make sure Python is installed on your system.
2. Save the script as `treasure_island.py`
3. Run the program:

```bash
python treasure_island.py
