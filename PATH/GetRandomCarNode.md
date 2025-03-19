# GET_RANDOM_CAR_NODE

## Declaration
```cpp
// 0x588E1506
bool GET_RANDOM_CAR_NODE(float x, float y, float z, float radius, int minLanes, bool avoidDeadEnds, bool avoidHighways, Vector3* vecReturn, int* nodeId);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** radius
- **int:** minLanes
- **bool:** avoidDeadEnds
- **bool:** avoidHighways

### Results
- **bool**
- **Vector3*:** vecReturn
- **int*:** nodeId

## Description
Will return a random node to satisfy the specified conditions.