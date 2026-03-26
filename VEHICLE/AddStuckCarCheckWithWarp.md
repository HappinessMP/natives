# ADD_STUCK_CAR_CHECK_WITH_WARP

## Declaration
```cpp
// 0x3BCA4ACA
void ADD_STUCK_CAR_CHECK_WITH_WARP(int carIndex, float minMoveDistance, int checkFrequency, bool warpIfStuck, bool warpIfUpsideDown, bool warpIfInWater, int warpMethod);
```

### Arguments
- **int:** carIndex
- **float:** minMoveDistance
- **int:** checkFrequency
- **bool:** warpIfStuck
- **bool:** warpIfUpsideDown
- **bool:** warpIfInWater
- **int:** warpMethod

### Results

## Description
Will attempt to warp a vehicle out of a stuck or upsidedown or in water position.