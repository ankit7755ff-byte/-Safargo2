# 🐍 SAFARGO 2 — 3D Snake Royale

**Live Game URL:** [https://safargo2.vercel.app/](https://safargo2.vercel.app/)

A high-performance, real-time 3D multiplayer-style snake survival game with dedicated Gaming Homepage, Player Game IDs, Finger Touch Controls, and Real-Time Global Leaderboard.

---

## 🌟 Naye Features (v3.0 Major Update)

### 1. 🏠 Brand New Gaming Homepage (Lobby)
- **Dedicated Landing Page:** Game shuru hone se pehle ek sleek cyberpunk portal milta hai.
- **Player Profile Pill:** Screen ke top-right me aapka Avatar, Player Name, **Game ID (`SFG-XXXXX`)**, aur Coins Wallet balance dikhta hai.
- **Game Modes:**
  - 👑 **Battle Royale:** 10 snakes, shrinking safe zone ring, last snake standing.
  - ⚡ **Turbo Rush:** Fast-paced speed frenzy with giant food orbs.
  - 🛡️ **Endless Growth:** Casual survival mode to grow as big as possible without ring shrinking.
- **Daily Rewards:** Har 24 ghante me **100 🪙 free coins** claim karne ka button.
- **Skins Wardrobe:** 11 custom snake skins (Sunburst, Red Viper, Emerald, Golden Cobra, Shadow Monarch, etc.) coins se unlock karne ke liye.

---

### 2. 👤 Login, Sign Up & Permanent Game ID System
- **Auto-Generated Game ID:** Har naye player ko ek unique permanent Game ID milti hai (jaise `SFG-79315`).
- **Profile / Sign Up Modal:**
  - Apna custom Player Name chunein.
  - 12 high-resolution Avatar emojis (🐍, 🐉, 👑, ⚡, 🦁, 💎, 💀, 🤖, 🐯, 🦅, 🔥, 🏆).
  - 4-digit Security PIN set karein taaki aapka account aur coins surakshit rahein.
- **One-Click Guest Play:** Bina password ke direct instant play with guest Game ID.
- **Clipboard Copy:** Game ID ke paas **"📋 Copy Game ID"** button diya gaya hai.
- **Profile Stats:** Total matches played, total kills, best mass score, win count, aur rank tier (Bronze, Silver, Gold, Platinum, Diamond).

---

### 3. 👆 Ungli Se Snake Control (Finger Touch & Slither Steer)
Mobile users ke liye snake control ko bilkul natural aur buttery smooth banaya gaya hai:
- **👆 Direct Finger Follow (Ungli Se Control):**
  - Screen par kahin bhi ungli rakh kar drag karein — snake turant aapki ungli ki disha me move karega!
  - Ungli ke neeche ek animated glowing neon **Touch Ring / Pointer** dikhta hai.
  - **Double-Tap Boost:** Screen par jaldi se double-tap karke hold karne par Turbo Boost accelerate hota hai!
  - **Two-Finger Hold Boost:** Screen par 2 ungliyan rakhne par bhi Turbo Boost chalu ho jata hai.
- **🔲 4-Way D-Pad Buttons:** Screen ke left side me arcade style ▲ ◀ ▶ ▼ buttons (vibration feedback ke sath).
- **🕹️ 360° Virtual Joystick:** Smooth floating analog thumbstick.
- **⚡ Dedicated BOOST Button:** Screen ke right bottom me glowing turbo boost button.
- *Controls Mode aap Homepage par ya game ke andar top button se kabhi bhi badal sakte hain!*

---

### 4. 🏆 Real Global Leaderboard
- Real-time dynamic leaderboard system jisme har match ke scores record hote hain.
- **Top 10 Champions:** Medals (🥇 Gold, 🥈 Silver, 🥉 Bronze), Player Names, unique **Game IDs**, Mass Scores, aur Kills show karta hai.
- **Player High Score Tracking:** Aapka Game ID aur high score automatically leaderboard me rank hota hai aur card ke bottom me aapki exact rank highlight hoti hai.

---

### 5. 💰 Adsterra Monetization & Earning Ready
Game me high-CTR earning zones pehle se integrate hain:
1. **Adsterra Direct Link (`window.ADSTERRA.directLink`):**
   - **Second Chance Revive:** Maut ke baad 5-second countdown modal me player revive kar sakta hai (4s Golden Shield ke sath).
   - **Claim 2X Coins:** Game Over hone par coins ko 2 guna claim karne ka rewarded trigger.
   - **Periodic Game Over Ad:** Har 2 matches baad popunder trigger.
2. **Banner Ad Slots:**
   - Homepage Top Banner (728x90 / Responsive)
   - Homepage Bottom Banner (300x250)
   - Game Over Screen Banner
   - *Code me clearly tagged comments hain:* `<!-- [ADSTERRA AD CODE] Paste your script here -->`

---

## 🛠️ Adsterra Connect Kaise Karein:

1. `index.html` kholein aur line 45 par apna Direct Link paste karein:
   ```javascript
   window.ADSTERRA = {
     directLink: 'https://www.profitablecpmrate.com/YOUR_DIRECT_LINK_HERE',
     enableReviveAd: true,
     enableDoubleCoinsAd: true,
     gameOverAdEveryNMatches: 2,
   };
   ```
2. Homepage banner ke liye `id='homeAdTop'` aur `id='homeAdBottom'` me apna Adsterra script tag paste kar dein.

---

## 🚀 Controls Summary
| Action | Mobile / Touch | PC (Keyboard & Mouse) |
|---|---|---|
| **Steer Snake** | Ungli se drag karein / D-Pad / Joystick | Mouse move ya Arrow Keys / W, A, S, D |
| **Turbo Boost** | ⚡ BOOST button / Double-tap / 2-finger touch | Spacebar hold ya Left Mouse Click |
| **Switch Controls** | 🎮 Quick toggle button (Top corner) | P ya Esc for Pause menu |
| **Pause Game** | ⏸️ Pause button | P key / Escape key |
