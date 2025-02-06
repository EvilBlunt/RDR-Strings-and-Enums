## Known Natives that use this enum

| Native | Hash |
| :------------ | :------------: |
| INVENTORY::ACTOR_HAS_VARIABLE_MESH | 0xA091179F |
| ENTITY::ACTOR_IS_VARIABLE_MESH_ENABLED | 0x5DE31288 |
| ENTITY::ACTOR_ENABLE_VARIABLE_MESH | 0xDA2F6203 |

## Enum
```cpp
enum ePlayerVariableMesh
{
	// Player Model Mesh Values/Names (The amount of variable mesh can mix up with different outfits some oufits have 8 and some can have all).
	// ACTOR_PLAYER, ACTOR_PLAYER_JACK, can only use (0-21, 23, 25-30).

	PLAYER_MESH_Bandolier_Bullets = 0,
	PLAYER_MESH_Bandolier_Bullets2 = 1,
	PLAYER_MESH_Bandolier_Bullets3 = 2,
	PLAYER_MESH_Bandolier_Bullets4 = 3,
	PLAYER_MESH_Bandolier_Bullets5 = 4,
	PLAYER_MESH_Bandolier_Bullets6 = 5,
	PLAYER_MESH_Bandolier_Bullets7 = 6,
	PLAYER_MESH_Bandolier_Bullets8 = 7,
	PLAYER_MESH_Bandolier_Bullets9 = 8,
	PLAYER_MESH_Bandolier_Bullets10 = 9,
	PLAYER_MESH_Bandolier_Bullets11 = 10,
	PLAYER_MESH_Bandolier_Bullets12 = 11,
	PLAYER_MESH_Bandolier_Bullets13 = 12,
	PLAYER_MESH_Bandolier_Bullets14 = 13,
	PLAYER_MESH_Bandolier_Bullets15 = 14,
	PLAYER_MESH_Bandolier_Bullets16 = 15,
	PLAYER_MESH_Bandolier_Bullets17 = 16,
	PLAYER_MESH_ShortArm_Bullets = 17,
	PLAYER_MESH_ShortArm_Bullets2 = 18,
	PLAYER_MESH_ShortArm_Bullets3 = 19,
	PLAYER_MESH_ShortArm_Bullets4 = 20,
	PLAYER_MESH_ShortArm_Bullets5 = 21,
	PLAYER_MESH_Bandolier = 23,
	PLAYER_MESH_LongArm_Holster = 25,
	PLAYER_MESH_Bandana = 26,
	PLAYER_MESH_Left_Arm_Gloves = 27,
	PLAYER_MESH_Right_Arm_Gloves = 28,
	PLAYER_MESH_Left_Arm_No_Gloves = 29,
	PLAYER_MESH_Right_Arm_No_Gloves = 30
};

enum eActorVariableMesh
{
	// Non Player Actor Mesh Values/Names
	// Some are undead only ie head blown off meshes.

	ACTOR_MESH_Bandana = 0,
	ACTOR_MESH_Right_Arm_Gloves = 1,
	ACTOR_MESH_Left_Arm_Gloves = 2,
	ACTOR_MESH_Right_Arm_No_Gloves = 3,
	ACTOR_MESH_Left_Arm_No_Gloves = 4,
	ACTOR_MESH_ShortArm_Holster = 5,
	ACTOR_MESH_LongArm_Holster = 19,
	ACTOR_MESH_ShortArm_Holster_Pistol = 20, // ACTOR_COMPANION_Marshal only
	ACTOR_MESH_Head = 23,
	ACTOR_MESH_Knife_Holster = 23, // ACTOR_MISC_Son only
	ACTOR_MESH_Bonnet = 24, // Female Models
	ACTOR_MESH_Hair = 25,
	ACTOR_MESH_Head_Blown_Off = 29,
	ACTOR_MESH_Half_Head_Blown_Off = 30
};

enum eAnimalVariableMesh
{
	// Animal Mesh Values (Only Horse, Cows, Mule/Donkey).
	// Horses can only use (8, 9, 10, 11, 13, 15, 21, 22).
	// Mule/Donkey can only use (8, 11, 13).
	// Cows can only use (6).

	ANIMAL_MESH_Cowbell = 6,
	ANIMAL_MESH_Saddle = 8,
	ANIMAL_MESH_Saddle2 = 9,
	ANIMAL_MESH_Harness = 10,
	ANIMAL_MESH_Bridle = 11,
	ANIMAL_MESH_Rope_Bridle = 13,
	ANIMAL_MESH_Horse_Shoes = 15,
	ANIMAL_MESH_Forelock_Hooves = 21,
	ANIMAL_MESH_Unicorn_Horn_Hooves = 22
};
```