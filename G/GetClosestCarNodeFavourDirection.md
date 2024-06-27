# GET_CLOSEST_CAR_NODE_FAVOUR_DIRECTION

## Declaration
```cpp
// 0x2F2405D1
bool GET_CLOSEST_CAR_NODE_FAVOUR_DIRECTION(float x, float y, float z, float faceX, float faceY, float faceZ, float* outX, float* outY, float* outZ, float* outHeading);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** faceX
- **float:** faceY
- **float:** faceZ

### Results
- **bool**
- **float*:** outX
- **float*:** outY
- **float*:** outZ
- **float*:** outHeading

## Description
Will return if can the closest vehicle node, tries to return a heading which points the car in the right direction to reach face coords.