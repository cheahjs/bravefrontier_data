bravefrontier_data
==================

Holds extracted data for the game Brave Frontier (Global/JP/EU/KR)

#List of extracted data

* dictionary.json - Parsed strings from Global.
* dictionary_raw.txt - Raw dictionary file from Global.
* info.json - Unit data extracted using the script from https://github.com/Deathmax/bfdb/
* items.json - Item data extracted using the script at https://github.com/Deathmax/bfdb/
* items_light.json - Item data without recipe information.
* missions.json - List of missions, their energy costs and number of battles.
* files_list.txt - MD5 hashes of all data files from Global, and must-download files for JP.
* ai.json - AI actions
* bbs.json - List of all skills
* es.json - List of all extra skills
* evo_list.json - List of all evolution mats/costs.
* feskills.json - List of all SP enchancements.
* ls.json - List of all leader skills

#Automatic Updates

* Global currently has full data updates: dictionary, AI, units, items, missions
* JP has the following updates: AI, units, items, items (light).
  * items_light.json will be updated regardless of server status. items.json can only be updated when the server is up.
* EU has the following updates: AI, units, items (light)
* KR is no longer updated as the game has closed in KR.

#FAQ

**What's all the 'unknown' things in the unit and item dumps?**
Those are effects not yet parsed by the script. Global is currently the priority, followed by JP effects.
