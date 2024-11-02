# START_PTFX_ON_OBJ_BONE

## Declaration
```cpp
// 0x60980323
int START_PTFX_ON_OBJ_BONE(char* fxName, int objectIndex, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, int boneIndex, float scale);
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
- **int:** boneIndex
- **float:** scale (default size = 1.0)

### Results
- **int:** ptfxId

## Description
Start a particle effect on a object bone with an offset position and orientation.