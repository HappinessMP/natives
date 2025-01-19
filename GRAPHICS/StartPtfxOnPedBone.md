# START_PTFX_ON_PED_BONE

## Declaration
```cpp
// 0x2209116C
int START_PTFX_ON_PED_BONE(char* fxName, int charIndex, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, int boneIndex, float scale);
```

### Arguments
- **char*:** fxName
- **int:** charIndex
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
Start a particle effect on a character bone with an offset position and orientation.