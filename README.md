# Serpent Royale 3D — Snake Arena (-Safargo2)

A fast-paced, high-retention 3D Battle Royale Snake Arena with real leaderboards, tactile mobile controls, coin economy, and pre-wired Adsterra monetization triggers.

---

## 🚀 What's New in this Update (Naye Features)

### 1. 🎮 Dual Snake Controls (Mobile & Desktop)
* **4-Way Tactile D-Pad Buttons**: Ergonomic Up (▲), Down (▼), Left (◀), and Right (▶) buttons on bottom-left for instantaneous turning on mobile.
* **Smooth Virtual Joystick**: Alternative 360° touch analog stick.
* **Control Switcher Button (🎮)**: Toggle between **D-Pad Buttons** and **Virtual Joystick** anytime with one tap.
* **Dedicated Turbo BOOST Button (⚡)**: Large golden boost button on the bottom-right with haptic vibration feedback.
* **Desktop Support**: Arrow keys, WASD, Mouse steering, and Spacebar boost.

### 2. 🏆 Real Global Leaderboard
* Real-time Champions Leaderboard displaying Top 10 players worldwide with trophies (🥇, 🥈, 🥉), scores, and kill counts.
* Tracks your personal all-time high score and global rank badge.
* Viewable anytime via the **🏆 LEADERBOARD** button on Menu, Game Over, and HUD.
* Scores persist across sessions in local storage and auto-update upon achieving a new record.

### 3. 🪙 Coins Economy & Progression (High User Retention)
* **Earn Coins**:
  - Fruits eaten = +1 to +4 coins.
  - Snake eliminated = +25 coins.
  - Victory Royale = +100 coins.
* **Skin Store**:
  - 11 stylish skins (Sunburst, Red Viper, Emerald, Amethyst, Forest, Cyber Wave, Sakura, Shadow Monarch, Inferno Dragon, Ghost Silver, Neon Sovereign).
  - Unlock using in-game coins OR get a **Free Unlock with Ad**!

### 4. ❤️ Revive / Second Chance System (High CPM Adsterra Earner)
* When your snake is eliminated, a 5-second countdown offers a **Second Chance**.
* Tapping **⚡ REVIVE NOW** restores 65% of your snake length, pushes away enemies, and gives **4 seconds of Golden Invulnerable Shield**!
* Pre-wired to trigger your Adsterra Direct Link in a new tab.

### 5. 💰 2X Coins Claim on Game Over
* Doubles your match earnings with a single tap (triggers Adsterra Direct Link).

---

## 💸 Adsterra Connect Kaise Karein (Monetization Setup)

`index.html` open karein aur line ~445 par `window.ADSTERRA` configuration dekhein:

```javascript
/* =========================================================
   ADSTERRA MONETIZATION SETTINGS
   ========================================================= */
window.ADSTERRA = {
  // 1. Apna Adsterra Direct Link URL yahan paste karein:
  directLink: 'https://www.profitablecpmrate.com/your-adsterra-direct-link-here',

  // 2. Triggers (true = On, false = Off)
  enableReviveAd: true,          // Revive button click par ad trigger hoga
  enableDoubleCoinsAd: true,     // 2X Coins click par ad trigger hoga
  enableFreeSkinAd: true,        // Free Skin unlock par ad trigger hoga
  gameOverAdEveryNMatches: 2,    // Har 2 matches ke baad Game Over par ad trigger hoga
};
```

### Banner Ads Lagane Ke Liye:
1. **Adsterra Dashboard** se `300x250` Banner script copy karein.
2. `index.html` mein `<div class='ad-slot' data-ad='menu'>` aur `<div class='ad-slot' data-ad='over'>` mein script paste karein.

---

## 🕹️ Controls Guide
| Action | Mobile / Touch | Desktop |
|---|---|---|
| Steer Snake | D-Pad Buttons or Joystick | Mouse, Arrow Keys, WASD |
| Speed Boost | Hold ⚡ BOOST button | Hold Left Click or Spacebar |
| Toggle Controls | Tap 🎮 Button | — |
| Leaderboard | Tap 🏆 Button | Tap 🏆 Button |
| Pause Game | Tap ⏸️ Button | Press 'P' or 'Escape' |
| Mute Audio | Tap 🔊 Button | Tap 🔊 Button |
