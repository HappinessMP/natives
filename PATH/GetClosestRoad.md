# GET_CLOSEST_ROAD

## Declaration
```cpp
// 0x63C00DE7
bool GET_CLOSEST_ROAD(float x, float y, float z, float minLength, int minLanes, Vector3* southEndNode, Vector3* northEndNode, int* lanesGoingSouth, int* lanesGoingNorth, float* centralReservationWidth);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** minLength
- **int:** minLanes

### Results
- **bool**
- **Vector3*:** southEndNode
- **Vector3*:** northEndNode
- **int*:** lanesGoingSouth
- **int*:** lanesGoingNorth
- **float*:** centralReservationWidth

## Description
Will return if can the closest road segment of a certein length with a certain number of lanes.