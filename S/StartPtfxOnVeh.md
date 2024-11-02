# START_PTFX_ON_VEH

## Declaration
```cpp
// 0x5C4B1A8A
int START_PTFX_ON_VEH(char* fxName, int carIndex, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, float scale);
```

### Arguments
- **char*:** fxName
- **int:** carIndex
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
Start a particle effect on an car with an offset position and orientation.