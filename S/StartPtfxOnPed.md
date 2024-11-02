# START_PTFX_ON_PED

## Declaration
```cpp
// 0x381C1F1C
int START_PTFX_ON_PED(char* fxName, int charIndex, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, float scale);
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
- **float:** scale (default size = 1.0)

### Results
- **int:** ptfxId

## Description
Start a particle effect on an character with an offset position and orientation.