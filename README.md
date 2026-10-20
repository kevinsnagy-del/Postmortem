# POSTMORTEM *(beta)*

A roguelike mode for **LET IT DIE**, built on [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000). Choose **POSTMORTEM** on the title menu to start. It has its **own save**, so your normal game is not touched.

- **Random fighters** from your freezer. Death is permanent: a fallen fighter stays behind as a hater.
- **Every climb lands on a random floor** of the whole tower. Enemy strength follows how deep you are in the run, not the floor number.
- **Pick-1-of-3 rewards** from boxes and fully explored floors: weapons, armour, decals and upgrades. They equip themselves, and you choose which hand.
- **Lives** instead of kill-coin continues. Blood pacts, events and a hordelike run type.
- **Meta-progression between runs:**
  - unlock and construct gear;
  - buy drop tickets;
  - hub upgrades on the TDM terminal (a step-by-step upgrade tree);
  - achievements, a profile card and leaderboards.
- **Restored cut content:** four cut decals and 32 mushrooms for the mushroom effects the game handles but never used. Plus the console collab decals and gear.
- Its own title movie and title music.

This is a **beta**: lots of systems, some rough edges. Back up whenever you like with `ModDriveInstaller\Backup.bat`, and `RestoreSaves.bat` can restore only the POSTMORTEM save.

## Install

1. Install [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000) first.
2. Download `Postmortem-<version>.zip` from [Releases](../../releases), close the game, and unzip it into the LET IT DIE folder.
3. Run `ModDriveInstaller\Install.bat` again. It adds POSTMORTEM to the title menu and builds its art, title movie and music **from your own game files**. This takes a few minutes, and your files and saves are backed up first.

**Updates:** run `ModDriveInstaller\Update.bat` (betas update to newer betas). **Remove:** run `ModDriveInstaller\Remove.bat` and type `postmortem`. Your POSTMORTEM save `pmortem.sav` is kept.

## Credits

- The console collab decals and gear come from the community's collab packs, shipped unchanged:
  - s3er0i9ng's [LetItDieOfflineSafeContentInstaller](https://github.com/s3er0i9ng/LetItDieOfflineSafeContentInstaller);
  - Let It Revive ([Nexus](https://www.nexusmods.com/letitdie/mods/15), [source](https://gitgud.io/ClaudiaDiva/LID-QuestRevival)), with thanks to ZeroUnderOne.

  See `ModDriveInstaller/lib/Installer/packs/postmortem-collab/CREDITS.md` in the download. They are in their own pack, `postmortem-collab`.
- The title music is used with permission.

LET IT DIE belongs to GungHo Online Entertainment / Supertrick Games. This is an unofficial fan project.
