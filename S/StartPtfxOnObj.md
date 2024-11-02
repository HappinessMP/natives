# START_PTFX_ON_OBJ

## Declaration
```cpp
// 0xD8407E9
int START_PTFX_ON_OBJ(char* fxName, int objectIndex, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, float scale);
```

### Arguments
- **char*:** fxName
- **int:** objectIndex
- **float:** posX
- **float:** posY
- **float:** posZ
- **float:** rotX
- **float:** rotY
- **float:** rotZ
- **float:** scale (default size = 1.0)

### Results
- **int:** ptfxId

## Description
Start a particle effect on an object with an offset position and orientation.