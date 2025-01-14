## Bone Names

| **BONE NAME**  | **ENUM VALUE** | **DESCRIPTION**                                                                |
| :------------- | :------------ | :------------------------------------------------------------------------------ |
| NONE           | 0             | Default bone or no specific attachment point.                                   |
| ANKLE_R        | 1             | Right ankle bone, crucial for foot animations.                                  |
| ANKLE_L        | 2             | Left ankle bone, used for walking and running.                                  |
| KNEE_R         | 3             | Right knee joint, connects the thigh and shin.                                  |
| KNEE_L         | 4             | Left knee joint, used for crouching and leg bending.                            |
| HIP_R          | 5             | Right hip joint, part of the pelvic rotation.                                   |
| HIP_L          | 6             | Left hip joint, supports lower body movement.                                   |
| PELVIS         | 7             | Central pelvic bone, anchors the torso to the legs.                             |
| WRIST_R        | 8             | Right wrist joint, essential for holding weapons or objects.                    |
| WRIST_L        | 9             | Left wrist joint, used for dual-hand interactions.                              |
| ELBOW_R        | 10            | Right elbow joint, enabling arm flexing and aiming.                             |
| ELBOW_L        | 11            | Left elbow joint, allows for precise arm movements.                             |
| ARM_R          | 12            | Upper right arm, primary for pulling or holding.                                |
| ARM_L          | 13            | Upper left arm, used for balance or supporting actions.                         |
| CLAVICLE_R     | 14            | Right clavicle (collarbone), connects the shoulder to the chest.                |
| CLAVICLE_L     | 15            | Left clavicle (collarbone), supports upper body flexibility.                    |
| HEAD           | 16            | Head bone, controls facial animations and rotations.                            |
| NECK           | 17            | Neck bone, allows head tilt and rotation.                                       |
| SPINE01        | 18            | Lower spine bone, supports the torso's lower section.                           |
| SPINE02        | 19            | Middle spine bone, part of the central backbone.                                |
| SPINE03        | 20            | Upper spine bone, connects to the shoulders.                                    |
| BALL_R         | 21            | Right ball of the foot, key for walking and balance.                            |
| BALL_L         | 22            | Left ball of the foot, aids in ground contact.                                  |
| NAIL_R         | 23            | Fingernail on the right hand, detail for close-up interactions.                 |
| NAIL_L         | 24            | Fingernail on the left hand, matches the right for symmetry.                    |
| TOE_R          | 25            | Right toe bone, used for stepping and dynamic movements.                        |
| TOE_L          | 26            | Left toe bone, assists in stable footing.                                       |

## Enum

```cpp
enum ePedBone
{
	NONE = 0,
	ANKLE_R = 1,
	ANKLE_L = 2,
	KNEE_R = 3,
	KNEE_L = 4,
	HIP_R = 5,
	HIP_L = 6,
	PELVIS = 7,
	WRIST_R = 8,
	WRIST_L = 9,
	ELBOW_R = 10,
	ELBOW_L = 11,
	ARM_R = 12,
	ARM_L = 13,
	CLAVICLE_R = 14,
	CLAVICLE_L = 15,
	HEAD = 16,
	NECK = 17,
	SPINE01 = 18,
	SPINE02 = 19,
	SPINE03 = 20,
	BALL_R = 21,
	BALL_L = 22,
	NAIL_R = 23,
	NAIL_L = 24,
	TOE_R = 25,
	TOE_L = 26,
};
```