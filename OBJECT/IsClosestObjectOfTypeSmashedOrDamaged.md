# IS_CLOSEST_OBJECT_OF_TYPE_SMASHED_OR_DAMAGED

## Declaration
```cpp
// 0x788026F4
bool IS_CLOSEST_OBJECT_OF_TYPE_SMASHED_OR_DAMAGED(float x, float y, float z, float radius, int modelHash, bool isSmashed, bool isDamaged);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** radius
- **int:** modelHash
- **bool:** isSmashed
- **bool:** isDamaged

### Results
- **bool**

## Description
Gets the closest object (within the defined sphere) with the given modelHash and returns TRUE if it is smashed or damaged.