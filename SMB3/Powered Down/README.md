# Super Mario Bros. 3 - Powered Down

My Powered Down hack is simply a no-power-up mode for SMB3 that I was inspired to create when doing a no-power-up run of the base game. Why? Mostly for the learning exercise, but it also completely eliminates the option to use power-ups or skip levels. I also found that some levels are normally unbeatable without power-ups, so I changed those. Otherwise, levels and game difficulty are unaltered.

## Patching

[Floating IPS](https://www.romhacking.net/utilities/1040/) is recommended for patching. This requires you supply your own Super Mario Bros. 3 (USA) ROM. There are patches for both the Rev 0 and Rev 1 (aka PRG0/PRG1) versions, but since the hack was developed off of Rev 1, the ending patched result is the same, i.e. it will contain the Rev 1 changes.

## Compatibility

Tested on emulation through Mesen on Windows 10 and real hardware through EverDrive N8 Pro.

## Credits

All hacking was done by me.

SMB3-specific utilities used in the development of this hack:
- [SMB3 Foundry and SMB3 Scribe](https://github.com/mchlnix/SMB3-Foundry) by Michael Nix
- [SMB3 Disassembly](https://github.com/captainsouthbird/smb3) by Southbird

## Complete Change List

- World map changes:
	- Hammer Bros. (and therefore coin ships) removed
	- Mushroom houses removed
	- Some rocks removed since hammer is unattainable
	- Paths rearranged to make all remaining levels mandatory
	- "N-Spade" card matching game does not spawn
	- Hand Traps in World 8 always grab you
- Ability to attain any power-ups/items removed:
	- No mushroom houses
	- No white mushroom houses
	- No warp whistles
	- No in-level power-ups. Mostly replaced with single coins, sometimes a multi-coin or 1up
	- No level end items (Hammer Bros, Piranha Plants, Hand Traps)
	- No "N-Spade" card match items
	- No items with Princess letter at end of world
- Levels changed to be beatable without power-ups:
	- 6-5, 7-Fortress 1, 7-7, 8-Fortress
- Miscellaneous changes:
	- End of world loads directly into the next world without showing a princess letter. Decided on this rather than trying to rewrite hints to make more sense in the context of a no power-up hack
	- Title screen skips directly from curtain to game select, so as to not show powered-up Mario and Luigi
	- Ending scenes are unaltered. Although they depict power-ups, changing these in a satisfying way proved to be more difficult than it's worth for a non-gameplay effect