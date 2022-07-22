# pr4m0d's MISTer bins
#### Repo for MISTer core binaries

## Instructions for use
1) Each subfolder contains a core .rbf file and .mra file.
2) Copy the .rbf file and .mra file to your MISTer sd card in the appropriate areas.
3) Make sure the appropriate rom is also in the appropriate folder (see list below)
4) Run game via .mra file.

## Core Versions
- Armed Police Batrider (batrideru) - Release Candidate 1 07222022
- Battle Bakraid (bbakraid) - Release Candidate 1 07222022
- Battle Garegga (bgaregga) - Release Candidate 1 07222022
- Kingdom Grandprix (kingdmgp) - Release Candidate 1 07222022
- Sorcer Striker (sstriker) - Release Candidate 1 07222022

## Notes
- Battle Bakraid has EEPROM saving support. The default EEPROM is included in the mra. If you get a high score, choose "save settings" in the MISTer menu to save your score to the sdram in the config/nvram folder. It will automatically load back upon next launch of the game. I think unlocks are also stored in the EEPROM, but not sure as I have not played Bakraid much and don't know too much about its workings.

- The Garegga core is compatible with Garegga, Kingdom Grandprix and Sorcer Striker. The first byte sent in the MRA determines the mapper used in the core.

## License
MIT
