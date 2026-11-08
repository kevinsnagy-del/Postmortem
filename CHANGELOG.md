# Changelog

## 0.9.5-beta
- **Needs Mod Drive 9000 1.3.3** (Mod Drive updates itself first).
- **Fixed: a Jackal's kill skipped your lives.** The game sends a death by a Jackal straight to "game over"; with a life left you now get the continue as with any death.
- **The freezer holds up to 10 fighters.** A new save's freezer had room for 3, so the FIGHTER OFFERS upgrades had nowhere to put more. POSTMORTEM saves get the biggest freezer, and FIGHTER OFFERS now has 5 levels (up to 9 offers + your fighter).
- **Gear made by POSTMORTEM starts at full durability** (a high-level piece used to start at its level-1 durability).
- **Kill coins and SPIRIT show one number** -- no "/ maximum", never red.
- **No more "The quest has been updated."** in the achievement terminal.
- **Leaderboard:** a player with no score on any board no longer shows top overall points.
- **Prestiged decals glow on the skill bar** like they do in the menus.
- **New option "Skill bar rows":** rows of 9 above the bar (as before) or one continuous row.
- **A run floor's escalators stay closed until a kill opens them**: each enemy you defeat has a growing chance to open them (certain at the last one), and a message box tells you when they open. The elevator home is never locked.
- After a crash on the way off the first floor, the run-start rewards are given again.
- **Mid-bosses are tougher**: five haters' worth of HP (they had less than one and died to a single hit).
- The "collect them all" achievements (decal types, Premium 99 decals and gear, level-99 gear, research, titles) now end at the number the game actually has, and grow when more are added.
- **Every fighter starts at grade 1**; grades come only from levelling up in a run. The TDM upgrades BETTER FIGHTERS and FIGHTER TIER are removed.
- **Death Metal and Bloodnium moved into the currency box** (left of kill coins and SPIRIT); their separate box is gone.
- Fixed: the minimap showed no icons on run floors once SCOUT was bought.
- Fixed: the shrine prompt (with its gauge) never appeared.
- **Fixed: the game crashed on an escalator or elevator ride** when a weapon had more durability than the game allows. Gear is now kept at (just under) its true maximum -- chooser offers show full durability.
- **Fixed: reward armour was lost when you went to the hub** with a run suspended (weapons were kept, armour pieces were not).
- **The bank and the SPIRIT tank hold 9,999,999 from the start**; safe and tank levels no longer matter in POSTMORTEM. Gone: the "too much money" message, and the game cutting your bank down to the safe level (it held 50,000 at level 1).
- **Decals you already have are offered again** to stack (they almost never came up).
- **Your fighter's grade decides what powerups give**: equipment cards come at exactly your grade, and decal choices offer grades 1 up to your grade. The world tier only makes the enemies stronger.
- Escalator signs are blanked on every floor, not only the first one of a session; the fence / gate sweep also runs on every floor.
- Fixed: going home by elevator from floor 1 could load the hub twice.
- **Fixed: after a crash your run came back without its decals and its XP / world grade.** A resumed run keeps its decals, and the XP and world grade it had when the floor began.
- **Quit game on a run floor no longer kills your fighter.** The game closes at once and the next time you start POSTMORTEM you return to that depth, as after a crash. The quit question says so.
- **Continuing a run takes you back to the floor you left**, with the enemies you defeated and the chests you opened gone.
- **Every new floor gives a little XP on arrival**, so skipping a floor's fights still moves you (and the world) forward a bit.
- **A depth's chests pay once per run.** Leaving a floor through the hub (or a crash / Quit game) and coming back puts you on a new floor of the same depth: the chests you already opened there stay empty ("Already looted"). No more farming floor 1.
- **Blueprints and floor loot follow your fighter's grade** too (they still followed the world tier: grade 3 blueprints at fighter grade 1).
- The escalators are certain to open by the second-to-last enemy (a floor with one enemy: its kill).
- **Mail: Kiwako's page is now POSTMORTEM's.** POSTMORTEM writes to you there (a welcome mail first); MEIJIN's tips stay, Uncle Death's and Kiwako's vanilla mails are hidden.
- **The "you have mail" box never pops up any more**; new mail shows only as the badge on the rolodex's mail icon.
- Fixed: reward armour picked up during a floor could vanish when you went back to the hub (the chest piece was never handed to the save).
- Fixed: a powerup chooser could open while you were dying, interrupting the death.
- Fixed: one hater kill could give nine levels at once; a single kill now counts for a few levels at most.
- The minimap's RP is the current run's points again (points from runs that ended by death or a crash carried over).
- Fixed: "Already looted" never applied after continuing a run from the hub.
- The pause menu profile card sits a little further left of the currency window.
- Fixed: decal descriptions with several pages (set bonuses like King of Coal) ran out of the card.
- The in-tower part shop now says why it is closed instead of shutting silently.
- Fixed: a crash after taking gear -- reward gear's durability is now never above what the game allows.
- **Explosive elites blow up right after they die** (they waited until the body disappeared), and glow red during the fuse.
- Fixed: the shrine prompt was missing on the second floor of a run.
- Fixed: kills with a weapon could count as fist kills.
- Reward cards show the gear at full durability.
- Fixed: the event timer flickered (and could slow the game) during a Manhunt.
- All escalator destination signs are blank now (one could still name another area).
- The achievement pop-up sits in the bottom-right corner. "Random lockbox spots" moved to the Debug settings.
- **Fixed: starting POSTMORTEM on a new save crashed the game.** The freezer's random fighters could be a type the save had not unlocked in the normal game yet, and the game refused it with a crash. Every fighter type can now be offered on any save.
- **Fixed: the freezer's fighters were not free.** Each new offer quietly cost kill coins (1,000-4,000+). They cost nothing now, as intended.
- **Curses are back, as trade-offs.** A gamble shrine can now curse you with something that helps AND hurts. A curse lasts a number of kills, not a time, so it cannot be waited out; it carries over to the next floor until you have made the kills, and a pop-up says when it lifts:
  - **Glass Cannon** (8 kills): you hit much harder, but take 50 % more damage;
  - **Berserk** (6 kills): a big attack boost, but no healing while it lasts;
  - **Midas Touch** (10 kills): kill coins and SPIRIT come double, but more enemies are fired up -- some catch fire at once;
  - **Haunted** (10 kills): a Jackal hunts you, but every kill pays extra kill coins and SPIRIT (not in co-op).
- **Rebalanced with weapon mastery in mind:** a new fighter's first floors are quick (an ordinary enemy in about 2 hits, a hater in about 3, with a starter weapon), enemies climb in strength more slowly early and harder deep down, and reinforcements arrive sooner.
- **Haters wear decal builds:** every enemy fighter now has decals like yours -- one per decal slot of its grade, rarer ones in higher ranks -- for more varied fights. Lock onto a hater and the game's own info box shows its decals (they are also stuck on its body, as in the normal game).
- **No more hit cap -- enemy gear follows the world rank:** every hit lands in full, so your armour, HP and decals count again, and so do the enemy's. Enemies wear gear of the world rank's rarity (1 to 7), upgraded from level 1 to 99 as the rank goes on; from rank 8 their rarity-7 gear turns premium, up to premium 99 -- never past what you can have. Haters, Jackals and their decals all climb this ladder, and ordinary enemies grow with it. The world is never better researched than your own gear and decals: a new fighter meets enemies about as upgraded as it is.
- **Pop-up messages are back:** they had stopped showing in POSTMORTEM. A reward set aside (enemies near, backed out, or left unopened when the floor changes) says it waits in the pause menu (X).
- **Fixed: a run could start on a boss floor.** The first floor now keeps out the boss floors too, like every later ride (bosses from floor 10).
- **Fixed: Jackson's bomb timer and bomb count were missing.** Skipping the boss scenes also fast-forwarded the bomb counter, which switched the bombs off. Only real camera scenes are skipped now.
- **Fixed: lockdowns made the game laggier and laggier** (and it stayed laggy after the lockdown): the wall sparks never went away. They fade out now.
- **Fixed: backing out of a floor elevator counted as a ride back to the waiting room.**
- **Achievement pop-ups wait for the HUD** (loading screens, the powerup chooser) and then show in full; their text and the mushroom quality number are bolder.
- **Shrines use the game's bomb-disarm prompt**, so the prayer gauge shows while you hold the button.
- **The boss intro movie is skipped** (it played after pressing the boss button).
- **Achievement pop-ups always show, in the game's font:** the text no longer goes missing or switches to a plain font when the HUD hides or the map changes.
- **Blessings and curses pop up:** praying at a shrine shows what you got -- a blessing in the usual box, a curse in the red one.
- **New TDM upgrade DECAL SLOTS:** decal slots on the Equip skills board no longer depend on the fighter's grade. Every fighter gets +1 slot a level, up to 7, and a Skill fighter has 2 more (up to 9). A fighter that already had more slots from its grade keeps them.
- **New TDM upgrade STARTING STACKS:** every equipped decal starts the run with +1 stack a level, up to 5 (each equipped decal then starts at about two-thirds of its full strength).
- **No more kill-coin and SPIRIT caps:** the BANK and SPIRIT TANK upgrades are gone; your wallets hold up to 99,999,999 (anything above that is lost).
- **R&D metals follow the floor's grade** like other materials (no 5-star metal on floor 2).
- **Weapons picked up from the floor are not offered upgrades** in the reward chooser; weapons the chooser gave you still are.
- **Fixed: R3 did not turn the page** of an item's description in the reward chooser.
- **Achievement pop-ups appear in the lower right**, and Untouchable only counts floors where you fought.
- **Floor 1 can come up in a run now**, so every stamp floor is reachable. A floor's button-locked exit escalators open by themselves when you arrive, so a random arrival never leaves you stuck behind one (gates that need the mid-boss beaten stay as they are).
- **The stamp rally is POSTMORTEM's own:** a POSTMORTEM save starts with an empty stamp booklet (existing saves are reset once) and has its own rewards: every 5 tower stamps in a row pay a random reward -- kill coins, SPIRIT, Death Metal, Bloodnium or a bundle of skillshrooms -- and a full sheet (all 40 tower stamps, or all 10 Hazama stamps) gives a **random blueprint you have not found yet**, of a grade you have unlocked in the TDM (if there is none left, you get 8 times a set's reward instead).
- **Fighter types are unlocked in the TDM:** a new FIGHTERS tree with one upgrade per type -- Breaker, Collector, Defense, Lucky, Shooter, Skill and Tech -- bought in any order. The freezer only offers types you have unlocked; Balance is always open.
- **Weapon masteries start at level 1 in POSTMORTEM and are earned in runs** -- everyone starts equal on the leaderboard (existing POSTMORTEM saves are reset once; your normal game keeps its masteries).
- **The hub is fully open on a new save:** POSTMORTEM's save now has the hub as a played save has it -- the Fort terminal (upgrades and leaderboard) without the Death Match tutorial, every shop and character, the facility upgrades, and no tutorial pop-ups or first-time area cutscenes in runs. Your normal save is untouched.
- **Runs can start on a new save:** a POSTMORTEM save now has every elevator floor open, so the run's start floor is never missing (only the POSTMORTEM save; your normal save is untouched). Every player starts with the same floors.

## 0.9.4-beta
- **Needs Mod Drive 9000 1.2.0** (Mod Drive updates itself first).
- **The collab content is downloaded from its original authors** when POSTMORTEM is installed -- Let It Revive (Anon / Chromarex) and s3er0i9ng -- instead of being part of this download. Every file is checked against the original, and the collab decal stickers are rebuilt on your PC. POSTMORTEM cannot be installed without it. Credits: `ModDriveInstaller/lib/Installer/packs/postmortem-collab/CREDITS.md`.
- **Leaderboard:** much lighter on the network -- every board in one download every 2 minutes while the leaderboard is open, your scores sent at most every 10 minutes (a new record within a minute).

## 0.9.3-beta
- **Riding a floor elevator back to the waiting room saves the run** too, not only Tryptamine D and the Solo Shelter.
- **Co-op:** the party leader saves and continues the run; the others follow, and keep their levels, decals, powerups and lives for the session.
- **New achievements:** defeat fired-up enemies (and ones with two traits), dodge fired-up explosions, pray at shrines, receive every blessing, finish floors under 10 % HP, collect kill coins and SPIRIT, hold SPIRIT, Bloodnium and Death Metal at once, earn Bloodnium, bring gear to Premium 99, and a tier for every grade up to 7. "Spend" achievements for kill coins and SPIRIT became "collect".
- Shrines no longer curse you.
- **Leaderboard:** the server now also checks currency and run points between runs, and works out Overall itself.

## 0.9.2-beta
- **Continue runs later:** a run left with Tryptamine D or a Solo Shelter is saved, even if you close the game. The hub elevators offer CONTINUE with the run's stats (run points, waves, lives, world level), and X there ends the run.
- Continuing a run sends the bag's mushrooms, beasts and healing items to the storage locker (healing items that do not fit go to the reward box).
- Quitting no longer refills your lives: a resumed run keeps the lives it had.
- Fighters come only from the freezer's random offers: an empty slot can no longer buy one.
- **Leaderboard:** your record runs are checked by the leaderboard server before a Roguelike, Horde or Boss Rush best counts. An outdated version is told to update instead of failing silently.

## 0.9.1-beta
- Supports the LET IT DIE update of 2026-10-20 (Steam build 25923506).
- **Balance pass**: enemies get deadlier and more numerous with depth instead of tankier. Elite enemies with auras that grow with depth (fast, explosive, regenerating), reinforcements, gentler first floors and a cap on how much one hit can take.
- **Grade 7** (all four limit breaks) with 7 stars, rarity-7 gear drops, and automatic grade-ups.
- **Premium equipment**: upgrade gear past 99 for premium levels, about +1 % a level.
- **Super weapons**, a rebuilt **Hernia vending machine** (daily blueprint offers), and an online leaderboard on our own server.
- Shrines: hold A to pray, with a gauge.
- Weapon pickups always swap with the weapon in the chosen slot, even with a full bag.
- Falling out of the map puts you back where you stood (10 % HP).
- Boss cinematics skipped, no boss floors before depth 10, beasts and mushrooms allowed into runs, cleaner floor map, many fixes.

## 0.9.0-beta (first public beta)
- The POSTMORTEM roguelike mode: random fighters, random floors, depth scaling, pick-1-of-3 rewards, lives, blood pacts, events, hordelike runs.
- Meta-progression: blueprints, construction, drop tickets, the TDM upgrade tree, achievements, profile card, leaderboards.
- Restored cut content (4 decals, 32 mushrooms) and the console collab decals and gear.
- Own save, title entry, title movie and music.
