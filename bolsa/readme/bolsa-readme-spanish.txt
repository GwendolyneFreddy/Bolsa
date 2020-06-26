***********************************
*               Bolsa             *
*    Mod para Baldur's Gate II    *
***********************************


Bolsa es un nuevo vendedor, que como bien dice el nombre, vende contenedores varios, bolsas para los objetos que no te entren en el inventario, cinturones de munici�n y un Bast�n de Magus muy �til, adem�s de objetos normales.
(Descomprime este archivo en el directorio del BG2 y ejecuta el .EXE). 


Thanks and Credits
==================

- Idea: Alexa.
- Programaci�n y desarrollo: Mhoram.
- Gwendolyne: Updated translations, reviewed coding and fixed a few bugs (v6.0.0).
- Deratiseur: Released native EE compatibility version (v5).
- Traducci�n al italiano por ilot.
- L�neas extras y revisi�n por Miloch.
- Traducci�n al franc�s por Elgaern (de d'Oghmatiques)
- Gracias Lollorian (traducci�n al ingl�s) y White Agnus (revisi�n)
- AL|EN: Wrote Infinity Auto Packager tool which automatically provides Windows, Linux and Mac versions in the same archive file.
- Contacto SHS : http://www.shsforums.net/topic/60853-bolsa-updated-to-v600-with-ee-compatibility/
- Download SHS : http://www.shsforums.net/files/file/772-bolsa


- Contacto: http://www.clandlan.net/foros/index.php?showforum=9
- Web: http://corellon.clandlan.net


Versions History
================

Version 6.0.0 (June 26, 2020)
-----------------------------
- Added bolsa.ini metadata file to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Fixed a typo in `HANDLE_CHARSETS` function (replaced *infer_charset* with *infer_charset<ins>s</ins>*).
- Added `REQUIRE_PREDICATE` conditions to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "bolsa" `LABEL`.
- Added native EET compatibility.
- Fixed wrong and inaccurate ACTION.IDS patching.
- Fixed a bug creating Bolsa in Adventurer's Mart (AR0702) instead of the Five Flagons Inn 2nd Floor (AR0511).
- Staff of Magus (mhconti.itm):
	- Fixed wrong Speed Factor (1 - was 4) and weight (4 - was 3).
	- Modified opcode #20 (Invisibility) resistance: set to 3 Dispel/Bypass resistance.
	- Modified opcodes #101 (Immunity to effect) and #169 (Prevent portrait icon): set to 0 Natural/Nonmagical.
	- Added missing opcodes for a full Immunity to Charm effects: op#296 Protection from Specific Animation (SPNWCHRM), op#267 (protection from string = 8364 "Dominated" - 14780 "Dire charmed" - 1476 14672 "Charmed"). Fixed opcode #142 (Display Special Effect Icon) = replaced wrong parameter2 28 (Protection from Magic) with 52 (Mind Shield).
	- Removed ugly Protection from Evil glowing colors: Glow Pulse [9] effect.
	- Restored missing Protection from evil equipped effects and added DS values (117 PROTECTION_FROM_EVIL).
	- Fireball-Lightning Bolt ability: added Break Sanctuary flag for EE games.
	- Spell trap ability: replaced with STAF11.spl.
	- Added 1PP compatibility with EE games and classical 1PP modded games: Added Glowing staff animation (and colors) and harmonized colors item.
	- Appended tooltip.2da: added a new column if needed, and a new strref.
- Added foreign languages WeiDU prompts whenever possible.
- Updated .tra files for compatibility with GW_UPDATE_ITM_DESCRIPTION_TO_EE WeiDU function requirements which automatically removes usability restrictions for EE games.
- Updated and renamed readme files to "bolsa-readme-%LANGUAGE%.txt", then moved them into new "readme" folder.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

Version 5 (November 10, 2018)
-----------------------------
- Added native BG2EE compatibility by Deratiseur.
- Included BWP Fixpack: micbaldur's AR0511 script creating Bolsa compilation fix ( http://www.shsforums.net/topic/42220-fixes-for-the-big-fixpack/page-47#entry558339 ). 
- Thanks to Freddy_Gwendo for the code and the proofreading.
- Updated WeiDU installer to v246.

Version 4.1 (November 4, 2009)
------------------------------
- Traducci�n al italiano por ilot.

Version 4 (October 20, 2009)
----------------------------
- Traducci�n al franc�s por Elgaern.

Version 3 (September 20, 2009)
------------------------------
- L�neas extras y revisi�n por Miloch.

Version 2 (September 9, 2009)
-----------------------------
- Traducci�n al ingl�s gracias a Lollorian.
- White Agnus por la revisi�n.

Version 1 (May 15, 2009)
------------------------
- Initial release.
