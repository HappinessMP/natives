# GET_SAFE_POSITION_FOR_CHAR

## Declaration
```cpp
// 0x5D877285
bool GET_SAFE_POSITION_FOR_CHAR(float x, float y, float z, bool onlyOnPavement, float* pSafeX, float* pSafeY, float* pSafeZ);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **bool:** onlyOnPavement

### Results
- **bool**
- **float*:** pSafeX
- **float*:** pSafeY
- **float*:** pSafeZ

## Description
Checks to see if it can find a safe bit of ground to place a char.