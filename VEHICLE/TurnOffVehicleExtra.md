# TURN_OFF_VEHICLE_EXTRA

## Declaration
```cpp
// 0x5966824
void TURN_OFF_VEHICLE_EXTRA(Vehicle veh, int extra, boolean turnoff);
```

### Arguments
- **Vehicle:** veh
- **int:** extra
- **boolean:** turnoff

### Results

## Description
Switches an extra (1 to 9) off (`turnoff` = `true`) or on (`false`). Switching an extra on also repairs the whole vehicle. Use `TURN_ON_VEHICLE_EXTRA_NO_REPAIR` to keep the damage.