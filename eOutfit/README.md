## Known Natives that use this enum

| Native | Hash |
| :------------ | :------------: |
| OBJECT::GET_CURRENT_ACTOR_ENUM_VARIATION | 0xB54567B9 |
| OBJECT::SWITCH_ACTOR_ENUM_VARIATION | 0x7AB17813 |

###### John Marston Outfits (0, 1, 2, 3, 5, 6, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 4, 9) Undead Only (9, 14, 15, 21, 22, 23, 24).
###### Jack Marston Outfits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 13, 16, 17, 18, 19, 20) Can change to 12, 14, 15 but model is John Marston.
## Outfit Names
| TEXT LABEL | OUTPUT || TEXT LABEL | OUTPUT |
| :------------ | :------------ | :------------ | :------------ | :------------ |
| OUT_cowboy | Cowboy Outfit || OUT_suit | Elegant Suit |
| OUT_rebel | Reyes' Rebel Outfit || OUT_treasur | Treasure Hunter Outfit |
| OUT_dnd | Walton's Gang Outfit || OUT_rustler | Bollard Twins Outfit |
| OUT_bandito | Bandito Outfit || OUT_fbi | Bureau Uniform |
| OUT_uslaw | US Marshal Uniform || OUT_military | US Army Uniform |
| OUT_rancher | Rancher Clothing || OUT_legend | Legend of the West |
| OUT_social | Gentleman's Attire || OUT_duster | Duster Coat |
| OUT_poncho | Mexican Poncho || OUT_gun | Deadly Assassin |
| OUT_mount | Expert Hunter || OUT_bruise | Savvy Merchant |
| OUT_apoc_z | Legend of the Undead || OUT_zhunter_z | Army of the Undead |
| OUT_small | Union Suit || OUT_zombie | Undead Cowboy |
| OUT_apoc | Legend of the Apocalypse || OUT_zhunter | Undead Hunter |

## Enum
```cpp
enum eOutfit
{
	// John Marston Outfits (0, 1, 2, 3, 5, 6, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 4, 9) Undead Only (9, 14, 15, 21, 22, 23, 24)
	// Jack Marston Outfits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 13, 16, 17, 18, 19, 20) Can change to 12, 14, 15 but model is John Marston

	OUTFIT_OUT_cowboy,
	OUTFIT_OUT_suit,
	OUTFIT_OUT_rebel,
	OUTFIT_OUT_treasur,
	OUTFIT_OUT_dnd,
	OUTFIT_OUT_rustler,
	OUTFIT_OUT_bandito,
	OUTFIT_OUT_fbi,
	OUTFIT_OUT_uslaw,
	OUTFIT_OUT_military,
	OUTFIT_OUT_rancher,
	OUTFIT_OUT_legend,
	OUTFIT_OUT_cowboy2,
	OUTFIT_OUT_social,
	OUTFIT_OUT_apoc_z, // Injured John on RDR,
	OUTFIT_OUT_zhunter_z, // Injured John 2 on RDR,
	OUTFIT_OUT_duster,
	OUTFIT_OUT_poncho,
	OUTFIT_OUT_gun,
	OUTFIT_OUT_mount,
	OUTFIT_OUT_bruise,
	OUTFIT_OUT_small,
	OUTFIT_OUT_zombie,
	OUTFIT_OUT_apoc,
	OUTFIT_OUT_zhunter
};
```
