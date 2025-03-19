# GET_NTH_CLOSEST_CAR_NODE_FAVOUR_DIRECTION

## Declaration
```cpp
// 0x6F766824
bool GET_NTH_CLOSEST_CAR_NODE_FAVOUR_DIRECTION(float x, float y, float z, float faceX, float faceY, float faceZ, int node, Vector3* nearestNodeCoors, float* heading);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** faceX
- **float:** faceY
- **float:** faceZ
- **int:** node

### Results
- **bool**
- **Vector3*:** nearestNodeCoors
- **float*:** heading

## Description
Will return if can the closest car node, tries to return a heading which points the car in the right direction to reach FaceCoors.