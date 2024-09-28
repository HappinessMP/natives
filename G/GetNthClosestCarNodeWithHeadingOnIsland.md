# GET_NTH_CLOSEST_CAR_NODE_WITH_HEADING_ON_ISLAND

## Declaration
```cpp
// 0x59DB1AD1
bool GET_NTH_CLOSEST_CAR_NODE_WITH_HEADING_ON_ISLAND(float x, float y, float z, int nodeNum, int island, float* nearestNodeX, float* nearestNodeY, float* nearestNodeZ, float* returnHeading, int* numLanes);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **int:** nodeNum
- **int:** island

### Results
- **bool**
- **float*:** nearestNodeX
- **float*:** nearestNodeY
- **float*:** nearestNodeZ
- **float*:** returnHeading
- **int*:** numLanes

## Description
Will return if can the nth (n = 1 being closest) closest car node with a heading, to a coord on an island.