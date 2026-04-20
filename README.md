# Steel Wings: Last Stand

A browser-based vertical scrolling air combat shooter inspired by classic arcade games such as *1945 Air Force*.

---

## 🎮 Features

- Endless enemy waves
- Boss appears every 20 seconds
- 5-second break after defeating a boss
- Weapon upgrade system
  - Level 1 → 1 bullet
  - Level 2 → 2 bullets
  - Level 3 → 3 bullets
  - Level 4 → 4 bullets
  - Level 5 → 5 bullets
- Defeating a boss reduces weapon level by 2
- HP, Power Up, and Extra Life items
- Maximum of 3 lives
- Boss HP display
- Boss kill time display
- Pause / Restart / Back to Home buttons
- Sound effects with on/off toggle
- Detailed Game Over statistics

---

## 🕹️ Controls

### PC

- `Mouse` → Move fighter
- `WASD` or `Arrow Keys` → Move fighter
- `P` → Pause / Resume

### Mobile

- Touch and drag on the screen to move the fighter

---

## ⭐ Power-Up System

There are 3 item types in the game:

| Item | Effect |
|------|------|
| `HP` | Restore 1 HP |
| `P` | Increase weapon level by 1 |
| `1UP` | Gain 1 extra life |

Drop rates after defeating a normal enemy:

- 40% chance to drop an item
- If an item drops:
  - 35% → HP
  - 30% → Power Up
  - 35% → 1UP

Bosses always drop an item.

---

## 👾 Boss System

- A boss appears every 20 seconds
- A new boss will not appear until the previous one is defeated
- If a boss takes longer than 20 seconds to defeat, there is still a 5-second cooldown before the next boss appears
- Boss HP is shown above the boss
- When a boss is defeated, the game shows:
  - Time spent defeating that boss
  - Weapon level reduced by 2

Example:

```text
BOSS DOWN! 7.3s
FIREPOWER -2
```

---

## 💀 Game Over Screen

The Game Over screen shows:

```text
Final Score: 18420
Time Survived: 143.7s
Bosses Defeated: 5
Enemies Destroyed: 47
Fastest Boss Kill: 6.8s
```

---

## 🚀 How to Run

Play online with GitHub Pages:

```text
https://zhikai060.github.io/steel-wings-last-stand/
```

Or run it locally:

1. Download or clone this repository
2. Open the HTML file in your browser

```bash
git clone https://github.com/zhikai060/steel-wings-last-stand.git
```

Then open:

```text
index.html
```

No installation or additional libraries are required.

---

## 📁 Project Structure

```text
index.html    Main game file
README.md     Project description
```

---

## 🔊 Sound

The game includes:

- Shooting sound
- Hit sound
- Explosion sound
- Boss warning sound
- Power-up sound
- Game Over sound

Because of browser security restrictions, audio starts after the player's first interaction.

---

## 📌 Future Ideas

Potential future improvements:

- Multiple boss types
- Boss phase 2 patterns
- Item magnet system
- Enemy formations
- Best record / high score saving
- Background music
- Boss warning animation

---

## 📜 License

Free to use, modify, and share.


