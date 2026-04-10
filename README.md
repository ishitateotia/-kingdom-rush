# ⚔️ Kingdom Rush — Stack & Conquer!

> **Board2Code Hackathon 2026** | NPC — Lovely Professional University | April 9–10, 2026

---

## 🎮 About the Game

**Kingdom Rush** is a medieval turn-based strategy game built for the Board2Code Hackathon 2026.

Two kingdoms battle for glory! 7 warriors (Knight, Archer, Guard, Wizard, Dragon, Rogue, King) are all piled at the Castle Gate. March them through 9 treacherous territories to reach the Throne — but send them in the **right order** to earn bonus glory points!

---

## ✅ Rule Compliance

| Locked Rule | Implementation |
|---|---|
| ✅ Turn-based | Players alternate strictly, one action per turn |
| ✅ All tokens in one stack | All 14 warriors start stacked at slot 0 (Castle Gate) |
| ✅ Only top 1–3 interact | March & Reorder only affect the top 1–3 tokens |
| ✅ One action per turn | UI strictly allows only Move OR Reorder per turn |
| ✅ Forward only | March always goes +1 territory, never backward |
| ✅ End condition | All 7 warriors crowned OR 50 turns reached |
| ✅ Scoring system | Rank-based (70→61→52…) + up to 25pt order bonus |
| ✅ Working demo | Open index.html — zero setup needed |
| ✅ Core logic by team | 100% Vanilla JS, zero external libraries |

---

## 🕹️ How to Play

Open `index.html` in any browser and choose **vs AI** or **2 Kingdoms**.

### Actions (pick ONE per turn):

**⚔️ MARCH** — Move top 1, 2 or 3 warriors one territory forward  
**🔄 REORDER** — Rearrange the top 2 or 3 warriors in any order

### Scoring
- 1st to reach Throne: **70 pts**
- 2nd: **61 pts**, 3rd: **52 pts** (reduces by 9 each rank)
- Arrive in perfect order position: **+25 bonus pts**
- One position off: **+10 bonus pts**

---

## 🎨 Features

- 👑 Medieval fantasy theme — easy for anyone to understand
- ✨ Animated floating particles background
- 🔥 Fire particle burst on key moves
- ⚡ Screen flash on scoring moments  
- 🎊 100-piece confetti explosion on victory
- 🌟 Score pop-up animations
- 🤖 Strategic AI opponent
- 📱 Mobile-friendly responsive design
- 🏆 Live order-completion tracker

---

## 📁 Files

```
kingdom-rush/
├── index.html    ← Entire game in one file
└── README.md     ← This file
```

No installation. No setup. Just open and play.

---

Built for NPC Board2Code Hackathon 2026 | LPU Phagwara | Pool Prize ₹5 Lakh
