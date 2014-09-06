bravefrontier_data
==================

Holds extracted data for the game Brave Frontier (Global and JP)

#List of extracted data

* dictionary.json - Parsed strings from Global.
* dictionary_raw.txt - Raw dictionary file from Global.
* info.json - Unit data extracted using the script from https://github.com/bsuh/bfdb/
* items.json - Item data extracted using a modified version of the script at https://github.com/bsuh/bfdb/
* missions.json - List of missions, their energy costs and number of battles.
* files_list.txt - MD5 hashes of all data files from JP/Global.
* decoded_dat/ - Decrypted JSON files

#FAQ

**What's all the 'unknown' things in the unit and item dumps?**
Those are effects not yet parsed by the script. Global is currently the priority, followed by JP effects.
