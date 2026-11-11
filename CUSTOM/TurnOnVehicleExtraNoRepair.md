# TURN_ON_VEHICLE_EXTRA_NO_REPAIR

## Declaration
```cpp
// 0xB421B0B3
bool TURN_ON_VEHICLE_EXTRA_NO_REPAIR(int carIndex, int extra);
```

### Arguments
- **int:** carIndex
- **int:** extra

### Results
- **bool**

## Description
Switches an extra (1 to 9) of a vehicle on like `TURN_OFF_VEHICLE_EXTRA(carIndex, extra, false)`, but without repairing the vehicle. Health, dents, missing doors and windows, tyres and lights stay as they are, for the owner and for all other players.

Returns `true` if the extra is on afterwards and `false` if the model has no such extra.