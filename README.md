# Mine Muncher v2 - PWA Installation Guide

A Minecraft-themed Pac-Man game optimized for iPad landscape mode!

## New Features in v2

- **Larger game board** optimized for iPad landscape
- **Split horizontal controls**: Left hand = ◀▶, Right hand = ▲▼
- **7 Levels** (added 2 new easy levels)
- **Rules button** with full game instructions
- **Top 10 Leaderboard** with name entry for high scores
- **High scores persist** between sessions

## How to Install on iPad

### Option 1: Host Online (Recommended)

1. **Upload files** to GitHub Pages, Netlify, or Vercel
2. **On iPad Safari**, visit your hosted URL
3. Tap **Share** button → **Add to Home Screen**
4. Launch from home screen for full-screen play!

### Quick Deploy to GitHub Pages

1. Create new GitHub repository
2. Upload all files from this folder
3. Settings → Pages → Deploy from main branch
4. Access at: `https://YOUR-USERNAME.github.io/REPO-NAME`

## Game Features

**Characters:**
- 🧑 **Steve** - You control him
- 👤 **Villager** - Slow, easier to avoid
- 🟣 **Enderman** - Fast and aggressive  
- 🐉 **Ender Dragon** - Toughest enemy

**7 Difficulty Levels:**
- Level 1-2: Very Easy (1 mob, open layouts)
- Level 3-4: Medium (2-3 mobs)
- Level 5-7: Hard (3-5 mobs including dragons)

**Scoring:**
- 🟢 Emerald: 10 pts
- 🍎 Golden Apple: 50 pts + Power Mode
- 👻 Eating scared mob: 200 pts
- 🏆 Complete all levels: 1000 bonus

**Power Mode:**
- Golden Apples make enemies turn blue and flee
- Eat them for 200 points each!
- Lasts 8 seconds

## Controls

**iPad/Touch:**
- Swipe anywhere to change direction
- Left side buttons: ◀ LEFT  ▶ RIGHT
- Right side buttons: ▲ UP  ▼ DOWN

**Keyboard (computer):**
- WASD or Arrow keys to move
- P or ESC to pause

## Files Included

- `index.html` - Complete game
- `manifest.json` - PWA config
- `sw.js` - Service worker for offline play
- `icon-192.png` - App icon
- `icon-512.png` - Large icon

## Leaderboard

- Top 10 scores are saved locally
- Enter your name when you make the leaderboard
- Scores persist between sessions
- View anytime via 🏆 SCORES button

Enjoy! ⛏️🎮
