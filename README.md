HardcoreHUD (WoW Classic)
HardcoreHUD is a lightweight heads-up display addon for World of Warcraft Classic that keeps the most important survival information close to the center of your screen. It replaces the need to constantly look at default unit frames by presenting clean health/power bars, clear “danger” overlays, and a compact cooldown/utility row for quick decision-making—especially useful for Hardcore-style gameplay.

Features
Center-screen player (and optional target) health/power HUD bars
Clear warning overlays for low health / out-of-mana situations
Two-row cooldown layout:
Utility row: Healing potion, Mana potion (mana classes), Bandage, Hearthstone, and your racial ability (e.g. Escape Artist)
Class cooldown row: Shows key class defensives/mobility only when learned
Cooldown spirals + readable countdown text for spells and items
Bag-aware utility buttons:
Picks the highest-rank healing/mana potion available and binds it for click-to-use
Shows buttons dimmed/desaturated when you have none available
Combat-safe UI updates to avoid protected-action errors during combat
Compatibility
Developed and tested for World of Warcraft Classic (1.15.8).
Uses Classic-compatible APIs and avoids insecure UI operations in combat where possible.
Installation
Download the addon and place the HardcoreHUD folder into:
World of Warcraft/_classic_/Interface/AddOns/
Restart the game or run /reload.
Enable HardcoreHUD in the AddOns list on the character select screen.
Helpful Commands
/hhdbg — prints debug info about the HUD utility buttons (visibility, anchors, etc.)
/hhforce — temporarily forces utility buttons to the screen center for troubleshooting
Notes
Some elements only appear when relevant (e.g., mana potion button for mana users, class cooldowns only if learned).
If you find a missing racial/class cooldown, open an issue with your class/race and the spell name/ID.
