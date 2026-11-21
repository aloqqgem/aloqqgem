## Roblox Scripter · Luau

I build gameplay systems that hold up in a live game: server-authoritative, validated against exploits,
covered by tests, and tuned from one config file. Clean, readable `--!strict` Luau with comments that explain *why*.

### Projects

**[Inventory & Trading System](https://github.com/aloqqgem/inventory-trading-system)**
40-slot inventory, chests, player-to-player trading and DataStore saves.
Dupe-proof trades via a two-phase write that survives a server crash mid-trade, session-locked profiles,
anti-scam (locked offers, ready delay, change highlighting), request schemas and rate limits.
148 tests including a fuzz test over the real request path.

**[Fighting System](https://github.com/aloqqgem/fighting-system)**
M1 combos, block / parry / guard break, dashes with i-frames, a four-ability kit, ragdolls and training dummies.
Lag compensation (server rewinds targets to what the attacker saw), client-side prediction matched to server results,
an anti-cheat that snaps back speed hacks without ever kicking laggy players. 42 tests.

**[Soccer System](https://github.com/aloqqgem/soccer-system)**
Dribbling, curved and charged shots, slide tackles, volleys and bicycle kicks, a goalkeeper AI and a practice bot.
Server-owned ball with client-side prediction so shots leave the foot instantly; fully procedural animation
shared by players and NPCs, no uploaded animations.

### What I can do for you

- Combat, abilities, hitboxes, lag compensation
- Inventories, trading, shops, economies that can't be duped
- DataStore saving with session locking, retries and migrations
- Anti-exploit: remote validation, rate limits, server-side checks
- NPC / AI state machines, procedural animation, game feel (hitstop, shake, VFX, SFX)
- Clean UI built in code

### Contact

Discord: **aloqq69**. Open for commissions and long-term work.
