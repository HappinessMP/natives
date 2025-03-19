# HAS_FRAGMENT_ROOT_OF_CLOSEST_OBJECT_OF_TYPE_BEEN_DAMAGED

## Declaration
```cpp
// 0x31B64D2B
bool HAS_FRAGMENT_ROOT_OF_CLOSEST_OBJECT_OF_TYPE_BEEN_DAMAGED(float x, float y, float z, float radius, int modelHash);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** radius
- **int:** modelHash

### Results
- **bool**

## Description
This command works in a similar manner to HAS_OBJECT_FRAGMENT_ROOT_BEEN_DAMAGED but first finds the closest object with the given modelHash within the specified range.