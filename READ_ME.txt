BEYOND TWELVE - LEVEL 40 / PRIVATE WINDOWS INSTALL / 0.3.0.0

Send this ZIP to the Windows PC that has Baldur's Gate 3 installed.
No Toolkit, publishing, mod.io account or administrator access is required.

1. Close Baldur's Gate 3.
2. Right-click the ZIP and choose Extract All. Open the extracted folder.
3. Double-click INSTALL.cmd and read the result in the window.
4. Start BG3. Open Mod Manager > Installed and enable Beyond Twelve - Level 40.
5. Start a NEW test save. Keep this test separate from an existing campaign.

The installer copies the NORMAL release into this Windows user's mod folder:
%LOCALAPPDATA%\Larian Studios\Baldur's Gate 3\Mods

WHAT CHANGED IN 0.3.0.0
One feat/ability-improvement choice at every class level 13 through 40.
One XP per level-up from 1 to 40: 39 total XP to reach level 40.
For multiclass characters, added feats follow each class's own level.
Spell-slot progression and optional spell replacement remain included.

It checks the package's SHA-256 before installing. Previous builds with our
original BeyondTwelve40 versioned names (including FAST_TEST_ONLY) are moved
to a BeyondTwelve40-Backups folder next to Mods. Other mods, saved games and
load-order settings are left alone. Enable the mod yourself in the game.
INSTALL.cmd allows this PowerShell script for this process only; it does
not change the computer's saved PowerShell execution policy.

MANUAL INSTALL (same result, no script)
Press Windows+R, paste the mod-folder path above, and press Enter. Create
the Mods folder if it does not exist. Copy BeyondTwelve40_0.3.0.0.pak there.
Move any older BeyondTwelve40 or FAST_TEST_ONLY package out of Mods first.
Then follow steps 4 and 5. Do not copy the whole ZIP into Mods.

IF IT DOES NOT APPEAR
Confirm the .pak is directly inside Mods, not a subfolder, for the Windows
account running BG3. Restart the game. This package has passed file checks,
but has not yet been tested in BG3; share the exact error if it is rejected.

TEST RELEASE
All 12 official base classes have authored levels 13-40. Existing subclasses,
including Patch 8 additions, are intended to inherit parent progression.
Spell slots use class-specific tables and custom growth above level 20.
Added level 13-40 spell selectors require zero new picks; empty-list behavior
still needs gameplay testing. This mod does not add new spells or upcasts.
Custom spell mods that change class progressions may need compatibility work.
Disable other level-cap mods and remove any renamed copies of this mod.
One XP per level is now the main release's curve. This ZIP does not include
the older FAST_TEST_ONLY package, which lacks the new feat schedule.

TO REMOVE
Close BG3 and move BeyondTwelve40_0.3.0.0.pak out of Mods. Do not use removal
as a way to downgrade characters above the normal cap in a campaign save.

Official manual-install instructions:
https://baldursgate3.game/mods-how-to/
