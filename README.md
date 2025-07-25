# 🛡️ Defender: Echo Protocol  
> Retro-futuristic arcade shooter with a **color-shifting cyber-aesthetic** 🌈⚡  

https://defender-echo-protocol.vercel.app
---

## 🎮 What is it?
A fast-paced side-scroller where you pilot a neon triangle through **wireframe cyberspace**, blasting hostile programs while rescuing **8 lost data fragments** every wave.  
Each wave = **a totally new color theme**, so the whole world re-paints itself on the fly. 🔄

---

## ✨ Highlights
| Feature | Emoji |
|---|---|
| Dynamic palettes that cycle every wave | 🌅🟢👻🔴🌊 |
| Real-time synth soundtrack (Tone.js) | 🎹 |
| Perfect-run bonuses for saving every fragment | 💎 |
| Touch + keyboard controls | ⌨️📱 |
| Endless difficulty scaling | 📈 |

---

## 🚀 Quick Start
1. Clone or download this repo  
2. Open `defendergame1.html` in any modern browser  
3. **Click START GAME** (audio needs a user-gesture on mobile)  

---

## 🕹️ Controls
| Action | Keyboard | Touch |
|---|---|---|
| Move | WASD / Arrows | Virtual joystick (left) |
| Shoot | Spacebar | Big “SHOOT” button (right) |

---

## 🎯 Objective
- Survive each wave  
- **Rescue all 8 fragments** for the PERFECT bonus  
- Rack up points for extra lives (every 10 k)  

---

## 🎨 Color Themes
Swap the CSS `:root` block to test palettes instantly:

<details>
<summary><b>Neon Sunset</b></summary>

```css
--glow-color:#ff4d94; --background-color:#0d001a;
--enemy-color:#00e5ff; --fragment-color:#ffe100;
```
</details>

<details>
<summary><b>Matrix Green</b></summary>

```css
--glow-color:#33ff33; --background-color:#000500;
--enemy-color:#ff3333; --fragment-color:#ffff33;
```
</details>

<details>
<summary><b>Monochrome Ghost</b></summary>

```css
--glow-color:#ffffff; --background-color:#000000;
--enemy-color:#666666; --fragment-color:#cccccc;
```
</details>

<details>
<summary><b>Infernal Red</b></summary>

```css
--glow-color:#ff3300; --background-color:#1a0000;
--enemy-color:#ffcc00; --fragment-color:#66ff66;
```
</details>

<details>
<summary><b>Oceanic Deep-Sea</b></summary>

```css
--glow-color:#00e6ff; --background-color:#000b14;
--enemy-color:#ff3d71; --fragment-color:#00ffcc;
```
</details>

---

## 🔧 Tech Stack
- Vanilla JS (no frameworks)  
- Canvas 2D for visuals  
- Tone.js for live synthesis & reactive audio  
- Responsive flex layout + touch handlers  

---

## 🏆 Scoring Cheat-Sheet
| Event | Points |
|---|---|
| Destroy enemy | 100 |
| Rescue fragment | 1 000 |
| Wave clear bonus | 500 × fragments saved |
| Perfect wave | +5 000 |

---

## 📄 License
MIT — hack it, fork it, theme it, ship it.  
Show us your wildest palette swaps! 🎨
