# IS_VEHICLE_LIGHT_ENABLED

## Declaration
```cpp
// 0xFADB2E6A
bool IS_VEHICLE_LIGHT_ENABLED(int carIndex, int light);
```

### Arguments
- **int:** carIndex
- **int:** light

### Results
- **bool**

## Description
Returns `false` if the light was hidden with `SET_VEHICLE_LIGHT_ENABLED` on this client, otherwise `true`. Damage is not taken into account. See `SET_VEHICLE_LIGHT_ENABLED` for the light numbers.