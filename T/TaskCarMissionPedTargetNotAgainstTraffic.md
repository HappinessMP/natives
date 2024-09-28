# TASK_CAR_MISSION_PED_TARGET_NOT_AGAINST_TRAFFIC

## Declaration
```cpp
// 0x178332FF
void TASK_CAR_MISSION_PED_TARGET_NOT_AGAINST_TRAFFIC(int charIndex, int carIndex, int targetCharIndex, int carMission, float speed, int drivingMode, float targetReachedDist, float straightLineDist);
```

### Arguments
- **int:** charIndex
- **int:** carIndex
- **int:** targetCharIndex
- **int:** carMission
- **float:** speed
- **int:** drivingMode
- **float:** targetReachedDist
- **float:** straightLineDist

### Results

## Description
Same as TASK_CAR_MISSION_PED_TARGET, but car won't drive on the opposite side of the road into incoming traffic.