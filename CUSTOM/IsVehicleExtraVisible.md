# IS_VEHICLE_EXTRA_VISIBLE

## Declaration
```cpp
// 0x7D375835
bool IS_VEHICLE_EXTRA_VISIBLE(int carIndex, int extra);
```

### Arguments
- **int:** carIndex
- **int:** extra

### Results
- **bool**

## Description
Returns `false` if the extra was hidden with `SET_VEHICLE_EXTRA_VISIBLE` on this client, otherwise `true`. Whether the extra is switched on is not taken into account, see `IS_VEHICLE_EXTRA_TURNED_ON`. Also returns `false` if the model has no such extra.