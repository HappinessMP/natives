# CREATE_OBJECT

## Declaration
```cpp
// 0x4DE152A0
void CREATE_OBJECT(int modelHashKey, float x, float y, float z, int* objectIndex, bool registerAsNetworkObject);
```

### Arguments
- **int:** modelHashKey
- **float:** x
- **float:** y
- **float:** z
- **bool:** registerAsNetworkObject

### Results
- **int*:** objectIndex

## Description
Create an object with an offset (from the root the base) at the given coord.