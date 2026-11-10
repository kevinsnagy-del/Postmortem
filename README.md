# POSTMORTEM *(beta)*

A roguelike mode for **LET IT DIE**, built on [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000). Choose **POSTMORTEM** on the title menu to start. It has its **own save**, so your normal game is not touched.

This is a **beta**: lots of systems, some rough edges. Back up whenever you like in `ModDriveInstaller\ModDrive9000.exe` under **Backups**, which can also restore only the POSTMORTEM save.

## Features

### Three ways to play
- **Roguelike** (the express elevator): every climb lands on a **random floor of the whole tower**. Enemies get stronger with how deep you are in the run, not with the floor number.
- **Horde** (the ordinary elevator): survive waves in an arena, with Jackal waves and lockdowns.
- **Boss Rush** (the hub escalator): fight the tower's bosses one after another.
- **Easy, Medium and Hard**, and you can **start at any rank you have already reached**.

### Runs
- **Random fighters** from your freezer. Death is permanent: a fallen fighter stays behind as a hater.
- **Lives** instead of kill-coin continues. Quitting the game does not refill them.
- **Continue later:** ride a floor elevator back to the waiting room, or use Tryptamine D or a Solo Shelter, and the run is saved, even if you close the game. The hub elevators offer **CONTINUE** with the run's stats (run points, waves, lives, world level), and **X** there ends the run. Continuing sends the bag's mushrooms, beasts and healing items to the storage locker (healing items that do not fit go to the reward box).
- **Quit mid-floor** and the next launch puts you back on that floor, in the same run.
- **Level up on the floor** (X in the pause menu); levels reset when the run ends. Your **world level** and **grade** grow as you play, and grade-ups to **grade 7** happen by themselves.
- **12 blood pacts** chosen on the elevator, for more or less SPIRIT: No Hub Upgrades, Mythic, No Decals, Brittle, Masterwork, Hunted, Overtime, Locked Down, Fog of War, Safe Passage, Quiet World and Randomizer (random weapons and armour every floor instead of powerups).
- **Fall catch:** falling out of the map puts you back where you stood, at a cost of 10 % HP.
- **No boss floors** before depth 10, **boss cinematics skipped**, and **every gate and fence open** on every day.

### Rewards
- **Pick 1 of 3** from boxes and fully explored floors: weapons, armour, skill decals and upgrades. Gear equips itself and you choose the hand; picking up a weapon always swaps it with the one in the chosen slot, even with a full bag.
- **A starter weapon chooser** at the start of every run, and powerup choosers after horde waves and bosses.
- **Reroll** and **banish** in the choosers.
- **POSTMORTEM's own drop table**, which follows the depth: gear up to **rarity 7**, gated by your grade.
- **Lockboxes in random spots**, **lucky drops** from kills, and **reward rooms**.
- **Skill decals** that stack, with a skill bar.
- **Super weapons:** Death Toll, Hellhound Pair, Shadowpiercer, Thousand Fists, Bizarre Jojos, Yggdrasil and Shinigami, each with its own look and its own mechanic.

### Enemies and events
- **No damage sponges:** deeper means enemies that hit harder and come in greater numbers, not enemies with more health. The first floors are gentler, and no single hit can take more than a share of your health.
- **Elite enemies** with auras that grow with depth: **fast**, **explosive** and **regenerating**. Deeper floors bring **reinforcements**.
- **Random events**, more often the deeper you go: Ambush, Manhunt, Jackal Raid, Poison, Bomb, Bank, Legendary Beast, Lockdown, Blood Moon, Supply Drop, Cursed Floor, Thunderstorm, Heaven Detour, and a VIP to carry out.
- **Depth gloom:** the floors get darker the deeper you go (with or without Heavenly Designs).

### Blessing shrines
- Jizo, fox and monkey statues appear on floors; **hold A** to pray (a gauge shows the progress).
- Blessings: **Swiftness**, **Wrath**, **Iron Skin**, **Bloodthirst**, **Fortune**, **Jizo's Mercy** (one more life) and **Inari's Favour**; and there is **Monkeysanity**. Gamble shrines trade kill coins for a random blessing.

### Between runs
- **The TDM terminal is a hub-upgrade web:** damage and resistance per element (slash, blunt, fire, electric, poison, gunfire), Starting Lives, Second Wind, Floor Medic, Wave Medic, Bloodlust, Head Start, Extra Starters, Rerolls, Banish, Reward Quality, Reward Rooms, Lucky Drops, Treasure Nose, Explorer, Scout, Fewer Lockdowns, Longer Breathers, Lost Bag, Salvage, Bank, Spirit Tank, Dustin, Whetstone, Grade Up, Decal Mastery, Decal Offers, Focused Decals, gear and decal ticket magnets, Tuned Tickets, Blood Pacts, and the fighter upgrades (Fighter Freezer, Fighter Offers, Fighter Tier, Better Fighters, Skilled Fighters, Big Bags).
- **The freezer** offers random fighters; how many and how good depends on your upgrades. Rerolls are earned every few floors.
- **The Laboratory:** research unlocks gear for the drops, blueprints, drop tickets, and **premium** decals and equipment past level 99 (about +1 % a premium level, twice as strong at premium 99).
- **Hernia's vending machine, rebuilt:** daily blueprint offers for R-points, blueprint recycling, Today's Lineup (gear to start a run with), Extra Lives, a Reroll Pack and a Decal Pick.
- **Currencies:** kill coins, SPIRIT, Death Metal, Bloodnium, and bronze / silver / gold skill mushrooms, shown in the currency window. Dustin costs Death Metal per item.
- **The coin locker** can be expanded from the locker itself.
- The vanilla gear services, mails and tutorial cards that do not apply are closed, filtered or rewritten.

### Records and leaderboards
- **Achievements** in Naomi's terminal (the rolodex), with dailies, weeklies and monthlies that pay season points.
- **A profile card** with a title and a picture you unlock.
- **The floor map** shows the floors you have visited, by name.
- **Online leaderboards:** Overall, Roguelike, Horde, Boss Rush, Achievements and Run Points, all-time and per two-month season, with the past seasons kept. Record runs are checked by the leaderboard server, and a save that used debug tools does not post.

### Also
- **Restored cut content:** four cut decals and 32 mushrooms for the mushroom effects the game handles but never used. Plus the console collab decals and gear.
- **Co-op:** POSTMORTEM runs can be played together with [Let Us Die](https://github.com/kevinsnagy-del/LetUsDie); the party leader saves and continues the run, the others follow.
- Its own title movie and title music.

## Install

1. Install [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000) first.
2. Download `Postmortem-<version>.zip` from [Releases](../../releases), close the game, and unzip it into the LET IT DIE folder.
3. Open `ModDriveInstaller\ModDrive9000.exe` and choose **Apply mods to the game**. It adds POSTMORTEM to the title menu and builds its art, title movie and music **from your own game files**. This takes a few minutes, and your files and saves are backed up first.

**Updates and removal:** in `ModDriveInstaller\ModDrive9000.exe`, under **Mods** (betas update to newer betas). Your POSTMORTEM save `pmortem.sav` is kept.

## Credits

- The console collab decals and gear are **not part of this download**: Mod Drive 9000 downloads them from their original authors when POSTMORTEM is installed (checked file by file against the original; the decal stickers are rebuilt on your PC):
  - s3er0i9ng's [LetItDieOfflineSafeContentInstaller](https://github.com/s3er0i9ng/LetItDieOfflineSafeContentInstaller);
  - Let It Revive ([Nexus](https://www.nexusmods.com/letitdie/mods/15), [source](https://gitgud.io/ClaudiaDiva/LID-QuestRevival)), with thanks to ZeroUnderOne.

  with thanks to spiritovod. See `ModDriveInstaller/lib/Installer/packs/postmortem-collab/CREDITS.md`. An internet connection is needed the first time POSTMORTEM is installed.
- The title music is used with permission.

LET IT DIE belongs to GungHo Online Entertainment / Supertrick Games. This is an unofficial fan project.
