# 🧙 Anoma Intents Adventures

**Anoma Intents Adventures** is a **multiplayer top-down roguelike RPG** designed for the **Anoma Intents Game Challenge**.  
It is inspired by *Realm of the Mad God* and fully built around **Anoma’s intent system**.  
This project aims to win the rarest role on the island: **Wizard** 🧙.

---

## 🎮 Play Now

Invite the bot to your server:  
👉 [**Click here to invite Anoma Intents Adventures Bot**](https://discord.com/oauth2/authorize?client_id=1408016619862491217&permissions=67584&integration_type=0&scope=bot)

---

## ✨ Features

✅ All features currently in **👾┃intents-games**  
✅ Full character customization from **Intents Games**  
✅ Multiplayer roguelike RPG format  
✅ Top-down exploration with regions, quests, and permadeath  
✅ Powered by **Intents**: propose, join, commit, decline

---

## ⚔️ Core Commands

### 🧑 Character
- `p!create <race> <class>` → Create your hero  
- `p!profile` → View stats, XP, level  
- `p!inventory` → Check items  
- `p!race` / `p!class` (2500g) → Change race/class  
- `p!alignment` → Track your moral choices  
- `p!pet` / `p!petadopt` / `p!pettrain` → Adopt and train pets

### 📜 Quests & Regions
- `p!quest [easy|medium|hard]` → Start a quest  
- `p!region adventure start <region>` → Begin regional adventure  
- `p!region adventure continue` → Progress deeper  
- `p!region explore` → Face random events (with moral choices!)  
- `p!region status` → Check progress  
- `p!region abandon` → Escape with penalty

### 👾 Combat & Multiplayer
- `p!boss` → Fight world bosses  
- `p!summon` → Call for raid help  
- `p!duel @user` → Challenge other players  
- `p!leaderboard` / `p!lb` / `p!top` → Rankings  

### 💰 Economy
- `p!daily` → Daily rewards  
- `p!work` → Earn gold  
- `p!shop` → Buy items  
- `p!transfer @user <amount>` → Send gold  
- `p!bank` → Deposit/withdraw funds  

### 🌍 World & Strategy
- `p!caravan` → Manage trade routes  
- `p!property` → Buy/sell land  
- `p!army` → Train armies  
- `p!invade` → Wage war  
- `p!story [dungeon|wilderness|city|mystical]` → Generate lore stories  

### 🪄 Intents System
- `p!intent propose <action>` → Create intent  
- `p!intent list` → View available intents  
- `p!intent join <id>` → Join group intent  
- `p!intent commit <id>` → Commit to execution  
- `p!intent decline <id>` → Reject  

---

## ⚡ Quick Demo Script

Copy & paste these in your Discord server:

p!create tiefling warlock
p!profile
p!quest hard
p!region adventure start forest
p!region adventure continue
p!summon
p!intent propose raid --region forest
p!leaderboard level


👉 For full **multiplayer effect**, have a friend run:  
p!intent join <ID>
p!intent commit <ID>


---

## 🔧 Installation (for local devs)

```bash
git clone https://github.com/520money/Anoma-Intents-Adventures.git
cd Anoma-Intents-Adventures
pip install -r requirements.txt
cp .env.example .env   # add your Discord Bot Token
python main.py

🧩 Design Philosophy

XP Scaling: Level³ × 25 (extreme growth curve)

Permadeath: Dying resets progress (true roguelike)

Resource Scarcity: Gold is rare, items are plentiful

Moral Choices: p!region explore sometimes gives ethical dilemmas

Procedural Generation: 750+ items, 150+ skills, random events

Intents-first: Collaboration only happens via propose/join/commit

📜 License

This project is licensed under the MIT License – free to use, modify, and expand.




update README
