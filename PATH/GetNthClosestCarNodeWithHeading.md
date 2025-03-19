# GET_NTH_CLOSEST_CAR_NODE_WITH_HEADING

## Declaration
```cpp
// 0x1F6B3FF0
bool GET_NTH_CLOSEST_CAR_NODE_WITH_HEADING(float x, float y, float z, int nodeNumber, float* nodeX, float* nodeY, float* nodeZ, float* heading);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **int:** nodeNumber

### Results
- **bool**
- **float*:** nodeX
- **float*:** nodeY
- **float*:** nodeZ
- **float*:** heading

## Description
Will return if can the nth (n = 1 being closest) closest car node with a heading, to a coord.