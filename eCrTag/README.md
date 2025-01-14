## eCrTag

| **TAG NAME**        | **ENUM VALUE** | **DESCRIPTION**                                      |
| :------------------ | :------------ | :-------------------------------------------------- |
| None                | 0             | Default or no specific tag.                         |
| Label               | 1             | Represents a label tag, often used for identification. |
| Block               | 2             | Denotes a block tag, likely used for grouping elements. |
| Anchor              | 3             | Tag for anchors, used to mark reference points.     |
| Turn                | 4             | Represents a turn tag, possibly for directional data. |
| Event               | 5             | Event tag, used to signify events or triggers.      |
| Snapshot            | 6             | Snapshot tag, potentially for capturing states.     |
| Unknown             | 7             | Unknown or undefined tag.                           |
| GenericFloat        | 8             | Generic tag for floating-point values.             |
| GenericInt          | 9             | Generic tag for integer values.                    |
| GenericVector3      | 10            | Generic tag for 3D vector values.                  |
| GenericVector4      | 11            | Generic tag for 4D vector values.                  |
| GenericQuaternion   | 12            | Generic tag for quaternion data.                   |
| GenericMatrix34     | 13            | Generic tag for 3x4 matrix data.                   |
| GenericString       | 14            | Generic tag for string data.                       |
| GenericData         | 15            | Generic tag for raw or miscellaneous data.         |

## Enum

```cpp
enum eCrTag
{
	None = 0,
	Label = 1,
	Block = 2,
	Anchor = 3,
	Turn = 4,
	Event = 5,
	Snapshot = 6,
	Unknown = 7,
	GenericFloat = 8,
	GenericInt = 9,
	GenericVector3 = 10,
	GenericVector4 = 11,
	GenericQuaternion = 12,
	GenericMatrix34 = 13,
	GenericString = 14,
	GenericData = 15,
};
```