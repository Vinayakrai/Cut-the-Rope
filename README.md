# 🍬 Cut-the-Rope

**Cut-the-Rope** is a colorful, physics-based puzzle game where your goal is to slice ropes and drop a candy straight into the mouth of a cute blob character. With each increasing level, more ropes are added, creating a satisfying logic-meets-timing challenge!

---

## 🕹 Gameplay

- 🎯 **Goal**: Cut the correct ropes to drop the swirling candy into the happy blob’s mouth
- ✂️ **How to Play**:
  - Move your mouse over a rope to cut it (🔪 cursor appears)
  - Time your cuts carefully — don’t let the candy fall off-screen!
- 😊 **Win Condition**: Candy touches the blob!
- 💀 **Fail Condition**: Candy drops below the screen without reaching the blob

---

## 🔢 Levels

| Level | Ropes | Challenge                  |
|-------|-------|-----------------------------|
| 1     | 1     | Basic drop                  |
| 2     | 2     | Choose the right order      |
| 3     | 3     | Add some swing dynamics     |
| 4     | 4     | Multiple directions         |
| 5     | 5     | Precision and patience      |

---

## 🎨 Features

- 🍭 Swirling animated **candy**
- 🤖 Dynamic **rope physics** using Matter.js
- 🐸 Happy blob that changes expression
- ✂️ **Mouse-based slicing** interaction
- 🎉 Confetti celebration on final level win
- 🔄 **Replay** and **Next Level** options via popup
- 💥 Gradual **difficulty ramp-up**

---

## 🔧 Built With

| Tech         | Purpose                         |
|--------------|----------------------------------|
| HTML/CSS     | Structure and UI styling         |
| JavaScript   | Core logic and game mechanics    |
| Matter.js    | Physics engine (ropes, gravity)  |
| Canvas API   | Custom rendering for game visuals|

---

## 📸 UI Elements

- 🔢 Level Indicator (`Level 1`, `Level 2`...)
- 🔁 Replay Button at top-left
- 🧠 Popup overlay with Win/Retry messages
- 🍭 Animated Candy (red-white swirl with gloss)
- 🟢 Blobby Target (smiling or open-mouthed)

---

## 🎮 How to Play

1. Open `index.html` in your browser
2. Use your mouse to hover over and slice ropes (🔪)
3. Watch the candy fall!
4. Success: if it lands in the blob's mouth
5. Failure: if it falls off-screen
6. Beat all 5 levels to see 🎊 confetti!

---

## 🔄 Replay Options

After each level:
- 🔁 Replay
- ⏭️ Next Level (or Start Over if it’s the final level)

---

## Preview

![image](https://github.com/user-attachments/assets/de6a2e42-036d-4039-9e31-3a61eaf22afd)
![image](https://github.com/user-attachments/assets/cd984781-c353-4e46-b3ba-601de6b6cfa9)

---

## 🚀 Improvements You Can Try

- 🎯 Add scoring based on speed or number of cuts
- 🧠 Add timer-based challenges
- 🌐 Share your best run via localStorage
- 📱 Make mobile-friendly with touch slicing
- 🧩 Level builder for custom puzzles

---

## 📁 File Structure

| File            | Description                          |
|-----------------|--------------------------------------|
| `index.html`     | Main game logic, UI, and rendering  |
| `style` tag      | Game-specific CSS for layout        |
| `canvas`         | Render target for candy, ropes, blob|
| `Matter.js` CDN  | External physics engine             |

---

## 🧑‍🎨 Game Art & UX Notes

- 🍬 Candy has a white spiral + radial glossy shine
- 🧠 Blob is made of multiple green orbs + highlight
- 😄 Eye & mouth animations respond to success
- 🎊 Final win adds multicolored confetti shower

---

## 🧾 License

This game is made for educational and creative use. Feel free to modify or extend it in your own projects!

---

## 👩‍💻 Developed By

**Vinayak Rai**  
Creative coder passionate about combining animation, logic, and joy in games 🎮✨

---

