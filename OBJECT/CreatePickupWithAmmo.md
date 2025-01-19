# CREATE_PICKUP_WITH_AMMO

## Declaration
```cpp
// 0x1F736F00
void CREATE_PICKUP_WITH_AMMO(int modelHash, int pickupType, int ammo, float x, float y, float z, int* pickupIndex);
```

### Arguments
- **int:** modelHash
- **int:** pickupType
- **int:** ammo
- **float:** x
- **float:** y
- **float:** z

### Results
- **int*:** pickupIndex

## Description
Creates a weapon pickup, giving the player the specified amount of ammo when they pick it up.