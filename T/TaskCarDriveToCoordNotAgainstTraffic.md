# TASK_CAR_DRIVE_TO_COORD_NOT_AGAINST_TRAFFIC

## Declaration
```cpp
// 0x483A62AB
void TASK_CAR_DRIVE_TO_COORD_NOT_AGAINST_TRAFFIC(int charIndex, int carIndex, float coordsX, float coordsY, float coordsZ, float speed, int drivingStyle, int carModel, int drivingMode, float targetRadius, float straightLineDist);
```

### Arguments
- **int:** charIndex
- **int:** carIndex
- **float:** coordsX
- **float:** coordsY
- **float:** coordsZ
- **float:** speed
- **int:** drivingStyle
- **int:** carModel
- **int:** drivingMode
- **float:** targetRadius
- **float:** straightLineDist

### Results

## Description
Same as TASK_CAR_DRIVE_TO_COORD, but car won't drive on the opposite side of the road into incoming traffic.