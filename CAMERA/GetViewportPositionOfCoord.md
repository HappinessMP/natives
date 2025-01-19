# GET_VIEWPORT_POSITION_OF_COORD

## Declaration
```cpp
// 0x287A49A5
bool GET_VIEWPORT_POSITION_OF_COORD(float worldPosX, float worldPosY, float worldPosZ, int type, float* viewportPosX, float* viewportPosY);
```

### Arguments
- **float:** worldPosX
- **float:** worldPosY
- **float:** worldPosZ
- **int:** type (2: screen pos)

### Results
- **bool**
- **float*:** viewportPosX
- **float*:** viewportPosY

## Description
Returns a valid point on screen, if either x or y is invalid, this will return false and -1.0 for x and y.