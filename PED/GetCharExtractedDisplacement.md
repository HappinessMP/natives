# GET_CHAR_EXTRACTED_DISPLACEMENT

## Declaration
```cpp
// 0x466B5AA0
void GET_CHAR_EXTRACTED_DISPLACEMENT(int charIndex, bool worldspace, float* x, float* y, float* z);
```

### Arguments
- **int:** charIndex
- **bool:** worldspace

### Results
- **float*:** x
- **float*:** y
- **float*:** z

## Description
Gets the displacement (in meters) that will be applied to the given char this frame.

If worldspace is set to TRUE the result will be in world coordinates (absolute worldspace). If worldspace is set to FALSE the result will be in local coordinates (relative to the character).