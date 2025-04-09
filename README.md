🎯 HexBounties Skript

A fully-featured bounty system for Minecraft servers using the Skript plugin. Players can place PvP or PvE bounties on other players, or place mob bounties on hostile mobs like zombies or creepers. Includes a bounty GUI, compass tracking, click-to-track system, and auto-expiring bounties.

---

🌈 Gradient Prefix Support

HexBounties uses a customizable prefix with gradient color support via Skript add-ons like SkBee or MiniPlaceholders. Configure it in `options:` at the top of the Skript.

Example:
```skript
options:
    display-prefix: <gradient:#f7941d:#e74c3c>[HexBounties]</gradient> &7>
```

📦 Features

- ✅ Place player bounties (PvP or PvE types)
- ✅ Place mob bounties (any living mob type)
- ✅ GUI bounty boards for both players and mobs
- ✅ Click to track player targets with compass
- ✅ Auto-expiring bounties (default: 10 minutes)
- ✅ Vault economy integration
- ✅ Works from 1.16.5 to latest Minecraft versions

---

🔧 Requirements

- Skript (2.6+ recommended)
- SkQuery
- Vault
- EssentialsX or another Vault-compatible economy plugin

---

📁 Installation

1. Download and install the required plugins.
2. Place `HexBounties.sk` in:
   `/plugins/Skript/scripts/`
3. Reload Skript with:
   `/skript reload HexBounties`

---

💻 Commands

| Command                                     | Description                          |
|--------------------------------------------|--------------------------------------|
| /bounty <player> <amount> <pvp|pve>         | Place bounty on a player             |
| /bounty mob <mob> <amount>                 | Place bounty on a mob type (e.g. zombie) |
| /bounties                                  | View all player bounties (GUI)       |
| /bounties pvp or /bounties pve             | Filter player bounties in GUI        |
| /bounties mobs                             | View mob bounties (GUI)              |

---

🧠 How It Works

- Use `/bounty` or `/bounty mob` to place bounties.
- Bounties auto-expire after a set time.
- Player bounties can be tracked via the GUI and compass.
- When a target (player or mob) is killed, the killer receives the bounty reward.
- All bounty activity is broadcast server-wide.

---

⚙️ Configuration

Edit the top of `HexBounties.sk` to customize:

```skript
options:
    decay-time: 10 minutes   # Bounty expiration time
    min-bounty: 50           # Minimum bounty value
```

---

📢 Notes

- Only one bounty can exist per player or mob at a time.
- Mob names must be valid entity types (like `zombie`, `skeleton`, `creeper`).
- Tracking resets if target logs out or dies.

---

🧩 Want More?

Want mob leaderboard tracking, SQL storage, or Discord integration?  
Suggest it and we’ll expand HexBounties even more!

---

🔗 Created by: aponder.dev

## 💖 Donation

If you find HexBounties useful and would like to support its development, consider making a donation. Your support helps improve and maintain the project.

[Donate on Ko-fi](https://ko-fi.com/wazupbutrcup)  
[Donate on PayPal](https://www.paypal.com/donate/?business=6TUCF33LPY9K2&no_recurring=0&item_name=Development+and+Coding+Features&currency_code=USD)