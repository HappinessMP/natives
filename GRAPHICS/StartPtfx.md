# START_PTFX

## Declaration
```cpp
// 0x3A774777
int START_PTFX(char* fxName, float posX, float posY, float posZ, float rotX, float rotY, float rotZ, float scale);
```

### Arguments
- **char*:** fxName
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
Start a particle effect at a world position and orientation.